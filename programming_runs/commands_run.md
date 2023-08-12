python main.py \
  --run_name "simple_leetcode_python3_gpt4_visible" \
  --root_dir "root" \
  --dataset_path ./executors/leetcode_env/leetcode_dataset/data/humaneval/leetcode-hard-py-40-uncontaminated_tests.jsonl \
  --strategy "simple" \
  --language "py" \
  --model "gpt-4-0314" \
  --pass_at_k "1" \
  --max_iters "1" \
  --is_leetcode \
  --verbose

python main.py \
  --run_name "simple_leetcode_python3_gpt4_visible" \
  --root_dir "root" \
  --dataset_path ./executors/leetcode_env/leetcode_dataset/data/humaneval/leetcode-hard-py-40-uncontaminated_tests.jsonl \
  --strategy "simple" \
  --language "py" \
  --model "gpt-4-0613" \
  --pass_at_k "1" \
  --max_iters "1" \
  --is_leetcode \
  --verbose


python main.py \
  --run_name "reflexion_leetcode_python3_gpt4_react_constraints_visible" \
  --root_dir "root" \
  --dataset_path ./executors/leetcode_env/leetcode_dataset/data/humaneval/leetcode-hard-py-40-uncontaminated_tests.jsonl \
  --strategy "reflexion" \
  --language "py" \
  --model "gpt-4-0314" \
  --pass_at_k "1" \
  --max_iters "5" \
  --is_leetcode \
  --verbose

python main.py \
  --run_name "reflexion_leetcode_python3_gpt4_react_constraints_visible" \
  --root_dir "root" \
  --dataset_path ./executors/leetcode_env/leetcode_dataset/data/humaneval/leetcode-hard-py-40-uncontaminated_tests.jsonl \
  --strategy "reflexion" \
  --language "py" \
  --model "gpt-4-0613" \
  --pass_at_k "1" \
  --max_iters "5" \
  --is_leetcode \
  --verbose

