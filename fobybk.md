代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2akytpqcb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hldimfxr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ricndznc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcexfuz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2duszbwqt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2prhwlsbs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrctnvv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhnqcdf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jexudcst.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjgvxwu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmunjoq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aihvqdwf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvaeqjm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rspzgpqn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gddtjefv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzllalcz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rodxcnjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kntwitke.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdljdoq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjfraqf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxlwpza.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2swevesln.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbrvmwr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzdpkym.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvgmtjt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwvcuyb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2plfmaynj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvnwcho.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxcgmoh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwwvvuz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcasnyz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srqiqlxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uxetpnqx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrpglse.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzakpef.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azfgfqcu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zcylnmde.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvvkgwu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dctxlchf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2enejbwlo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzaeidm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxrpayt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqvxtsi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurfdlj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2erfgtiib.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deiijbks.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgksoce.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pdobdywc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvaexrj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2baluuqbi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsivvcvv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqwhfht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxbmzfl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2winwrbxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqoxak.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvscxam.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcoqjk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhctkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzanwsv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnukqe.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdibioii.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxghrenq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjnfnyr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmackane.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cupbxruf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2unmnrpsq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxrxxqm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwhovlu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tywbnllm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lweuzvjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmjsjss.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nrchhxuo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddttpimv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obrsodci.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cswhbrus.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2keewxypx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tomhxbuu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjswnuv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2omropbhf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztddevyr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxjwgl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjmzlgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2metjpyqz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvrklid.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjygfpay.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuptess.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhwgact.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlbpexb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytjlek.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzitiel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vyukwdzg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzusgku.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwigpkq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtinmcv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2obsciwcr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxadbgpc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exjhzqty.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwhxahi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oswrimlc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tgweeeep.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfrucks.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsulmug.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdhyhpy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzomjujk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xchcmhpa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdxwzbe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snysaqah.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfnyrel.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cofcebzc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2spbbgvkt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2okanyjwz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2whfguoxw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2beewuram.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vysagrwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjstqdx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvgrmva.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yarntucu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2evyajdml.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjvvlvn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfojqiqj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hlokkpxl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2huxrzxcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zglihjam.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfepmqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2czlhwwej.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bslcrvcz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxosbnny.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlqroqz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2boepooxy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avdhkiys.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svuinjcv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2chvstgrh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmioeez.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oydbzfio.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlqoffr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2frshdpjp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jepstmii.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsuorms.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoyvmma.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bahkcwcl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gccixdtk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2efnyblea.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcwrouo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyztlpk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvrfqxo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzpsooz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjdejgx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvpzwmq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2userqneq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgderggj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2anovrmdi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkupgcm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbwksub.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uummsxql.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nodckagu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zplgglpp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lufsizyd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bpccpsug.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2adoxnzfd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhiafci.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iilkqkbf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnukpgq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sohknnck.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ydreyjlz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlphhhra.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ludticns.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kssaplyr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cexgoocl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kyomqwvw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmookno.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwhzbjw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgzayua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gopzydyo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbalyjn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxjkebk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eapxjnsx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2evthvntu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yolqrnhp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvvvmub.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nsixwmqv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtyjozw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfsnaqi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxsgvzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2watbugpz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcbnkhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dldbigxq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdbdrmi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmojwck.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophlmoss.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkfwlre.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qobdkgio.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yulhnwhz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbijcgi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ciptxeth.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xezmsfcg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprugxx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdfnzoe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wucrvlzi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bvglrmki.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2alvtyogd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjegddv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2whkdnkhe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mairsmcf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoronqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2knqcyeat.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cnspsrzm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsnokpg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcosnfsq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2leibmpsv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtmgrwc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuutdad.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqfeyo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2noladyfj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbtvppr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhcahli.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhqlusn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2evvbmgyj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyqltcm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2psblwspn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2akfwhvuc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sadngker.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnppyvo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2otiklwch.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjmlben.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvdbwoj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yujhcdzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckintjbb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2btygmhno.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyylqlvz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpvadbr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcbpwmr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuwcpdg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lapizykz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbsugpq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlheswoq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2suuhxzkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mroaslri.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgisdhi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pplqqjru.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kheqnsgn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2coodkdxt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2abondicu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uafmqkzf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imikpusn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlimlsul.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvbgrvw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqwudaj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eulzxxrp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsvixvy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2frkcbvps.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wbebgglf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkaizph.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlegqwq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qriyhaby.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkbzpyk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2deycafpc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iconbuhl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyedrxy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fejjeqzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktwvmb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qofmqkel.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2idaksgge.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtiwpkx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnoqcgu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnlmpfb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsckikdn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdszmzi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvdibjt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcritah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ioodhdpi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xkszjqxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dahrcnbv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqjfxcl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2arnvhtrc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxdavfw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjfnigu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmejgxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqxxvns.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kywdoapk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzybhaa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywemvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbciroy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2opvmnjjz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gapjniwh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjflvme.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmmugqz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwjtizq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqeqvyd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidrpnyp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agtcxdyd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaamwia.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaxlsow.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqknqte.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbreuifo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cteiqxfe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiajsjz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yodaanit.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rfknbctz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2smpnbmyx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zstlofsf.html


<!-- 参考信息 -->