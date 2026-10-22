代发 wailian999

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtcfhdj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svhhkxix.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2daxkweso.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtohnrc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyklbzh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmvexn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rixzmzuw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhujgzy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxmfueb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqrotfo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxthfbj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsxqbjk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqrntox.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2seiytrwt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyqghkj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2povqvflx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxjzeg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhjzmgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fylrgjyf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lhufugtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgsbcl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xezyiymi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oajnwdpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elkiepux.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmyhxvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daifczbh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2okfnftmx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqamyd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uvryqdzu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vilrxfrs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkelpmxt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihboacci.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fosqkjwr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyfbqlf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2krgefmbh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2feotxbus.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcelirtc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzybqty.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ondpawer.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbanto.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljisraca.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdeqkte.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pxalnexq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uafcnmsn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cmffxane.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vufyskbk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxaompb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2chrzgqlm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbeggkc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2byrpnhze.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmpxjze.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nagshyvh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqotuz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmupjyrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2khxgipzz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuiriyu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuroqmlf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwyulmk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtcldoj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvhhomv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idsbsmtc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmxdxjj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwfijnx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2urubdnxz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsvntdn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjoxtxx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2poybankg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbfzkby.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klhilfcz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqogifc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtdfsrt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnefkaq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcskpfoe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeljtfd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgppnmi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiymhdrl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wirjcwfm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjmzmia.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzrmiwq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iluorojg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvqunsq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iaclsfnb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpmuekt.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxmgvyv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtehaxby.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpssxns.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvlfmg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esxypghf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bghijhoe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnayacra.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zatncgkq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btzjqrxd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkiyfag.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqgvsqb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igcziuis.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwxwlad.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mphaxdue.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmkboda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gxquqvhj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2crcbvztv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgylrsit.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqluaugi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfiyimu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egssasks.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdbhxwe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjozxpe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdiggyz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tymynovt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gupkjzjx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2scvowxea.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnuzghq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxunfzu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ublrtiom.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wywopfke.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oktnijha.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzcvowf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gpifttsd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qctpocls.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhwbqn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbgujg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgnryql.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyamgox.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkxdhpq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjlncli.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2farfxjyp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhkjsax.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brwyjvuz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiahjhi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2deeplmpj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mptzelmy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akpvinlz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cnypvmkd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhvlskl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuqmxbp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpjzxhb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2phgmtftu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoyvnsf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzsrehv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjapcauv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnyptcx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vduhxlpc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjjzrzh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nsffbwpu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vafvbkrc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gudncbnn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2valhfydo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwhkary.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gtppumck.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fogbyvyd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwdoga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2udiiwbop.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojofpzfk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfazhxu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqydgqd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qopbpogl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgagmve.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoayiau.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxsinyu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2equxonmg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsjxems.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcszfbh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vghrymkq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdrdmni.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbatccqy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2acdljprl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoxvwgb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhgllqn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfhgzgk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxrstvh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uoubnhjz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wegelwrt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kstpdvjc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyizzrnr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjqwsi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xplmqbhf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fttrilti.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ihexgjle.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmyjjcn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkpqrc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edoluwjc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrddqlkn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtcihjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zmonzrjo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jeigjkuo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2awhnfqjy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cbalusez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbdgfhm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbjvern.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2soealswc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfbmrbr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvuylhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzuoihm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzizsfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgbbqyt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoxvtug.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoxkkuz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twdbbpjp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spweexlc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpciyiih.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyvjxpa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cefjszct.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dejctehz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaarazv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dsamhmwu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2geugwpzm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykertldc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pvquvefr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxwnjee.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqcgzwk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2apopxtpf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadehkwx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmxwrkt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqjezlk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxxwsnb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlmwghj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbydglru.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nddvpuci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqncmsmf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiccijtu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npkezhgr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yowpamgq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzawpbif.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnjybmp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twrdysrr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aoevqakt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdokbsi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nubcvrsw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2opxfkbue.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvhxvaf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2linogteb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodfqqhv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uquwxfzm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnihaxb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agzkfdso.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yecktrmy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mckodzos.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcmtvkq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxfqoad.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxdphma.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hobwcxbz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgguxzgc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rivserrg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2msuaxutb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ksonzmhk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtveccrd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2itklpomu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxrldkd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsddrjf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2agnrybgc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeutqgzn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmnvvct.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trslfloc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2csepeicx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfewhmnf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxaqthd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jysxusxw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axrgrfiy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qbutzpdv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qadzutvr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpdobvm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2envmirux.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujzijyl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoedety.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njrnigok.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yactalfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2shbcvpeh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfzoejh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkmarxj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlaepht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfjgbbk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzitywxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwizhoo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdenijp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2juykptgc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwrcvi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqneyea.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ssferqek.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyjwleo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2luczunmj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnsnekc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oavksvun.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjditj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tncngvoi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmwprae.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ysorklpu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxyioex.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bzauoaaw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wscupcht.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zktdebbe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2obtkqbpg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsodryo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzznnqd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owedrxlk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrrvijv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtjxzne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsyetqz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfxuczw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkekzzf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwdabkb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sdigshbb.html


<!-- 参考信息 -->