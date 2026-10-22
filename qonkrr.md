代发 wailian999

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrchiwxg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdzghmc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoubyya.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2itxottot.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxvfhfw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjuvnyj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rixeafpp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emujokxs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izkxqnaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqvdxst.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzamwog.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhawzrwf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrlymek.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwapbmj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrvrnfb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfcqsyo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lbstdigl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfchkec.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrzngd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhwnxgo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlcmjkm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmaawcy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmpykkb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2encfpgjq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2usvewdno.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2duzkdyoi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldlqknu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thajfmar.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxmfliu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiljtks.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfcqgoc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2brilumjo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoeprfg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvndgotr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqvxrmy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfrxbxp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxdnzpq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvhwmos.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjueulv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoblgbn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lymgvydj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvagsi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2regznrsk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbkhkhp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefrhpa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjlifna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwnvxr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkbivkg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqrydzd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbhhvjl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cslkwenk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfkbps.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uullsugs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritratca.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxghrigl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfqjwsk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2emuchmdp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhvjjrx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdmjsws.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczobzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnzwtd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2blqkfsho.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaftrcq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhinaxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uiymbajq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cscebljq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqpdjpn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2seqhehxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btmuyual.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbngcda.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbyqwks.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eknwjxhv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwvfhp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2apxyqtwn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjqllfk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsglzjn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjuxkqh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxdcrmo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzrwtth.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gofnzjes.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2duhypina.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nptwprcm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvvnect.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrekrkf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scnsdpji.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pelposdx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbimhti.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrbgoyd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qptpsqly.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjicmwg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfqxoea.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trngvvcw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoqsdng.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxihwpf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eksiupdc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvzudwv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjkztap.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpcvqd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbmsrum.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoespfy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2taeyhtwe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zpibngqe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yynskgbf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdazfgk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2napbgxsd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2befyxedw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhzksao.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqvxnci.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzhtzha.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kuipdktc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ymieivgj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjtgslh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ianavmxb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdkqoaf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjjskfl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjamyotr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkbwpw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeznddm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwfvono.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgxkhwp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrmhbve.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lzalmqfq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwowpwi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqjkurg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2avlrzpjf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhzctod.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlzkjmc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdgppde.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbklpjp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vssizhjd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaimfgt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxofggo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eoasqrzx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hovyuiiw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrctrjwr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfqftwh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmzrhwa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjvphnb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fokjuiuy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxccyco.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uljmqngn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxbhvta.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evwwhyeo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nkewxeoc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqrtcnp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlaiiyv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dytkuddb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2osbxjrfr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoqmtwc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjokwwcq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2emjsbdvw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tsngixin.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsrzkaj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnloanqx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jaywwcfw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhtdtml.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuaccse.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nciovspm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwfhiiu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2glzhxsjk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvslqof.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2moqsfxkl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2coxgstqt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvbbofc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2yswoqfuo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnybwyb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjjitwe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qqslxrvz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsefqul.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2phofduzz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqfwtyk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhmeep.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cofamrbi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbxtqfq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2niknilcq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrfljza.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjlicam.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bwchqpyw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfcpge.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmynzymw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pnswjpzh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhaghpg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scnvkzgd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpdllpd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhlrvvu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhzxzoy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2klywnurh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2asoydgis.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wybsbnlv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtpnpyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuoerjl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ejakezqw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nimttdcf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpisgex.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzlzebw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdvqnq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoiblit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuesorc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqwgygq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ignkvzlw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvatouhr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpgjiln.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vagzouuw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctagfyvx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqzpzcx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vftyjopi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkthbcyo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmriisx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtbltku.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oizsonbr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvaimbe.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2moklliqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2taprqdgh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yewltxbg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2guerzhlg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2njyhkglw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ucctwwxs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubffuuxt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdksgvvp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnljqks.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmtjxse.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixqsysb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbtbfbr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oacgqbfr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnoaiho.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjuvvzt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2giprrcfi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nviefcyh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfzynr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2epehmvsq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ypypbmzu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2niaamuah.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhoucrk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emqstmyb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ludzykxo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzznagi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqngiqw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlpxgnn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vivbqaaz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bljmulwd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrjzhmf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jwowcnew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2owktuxrz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsvjjgf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefneuaz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshutfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxacpogy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uuheayif.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eetbyjsc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaiuxkp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpepknd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbhlbye.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuntizr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2deeutrca.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnghmcl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2legvzuba.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mortlvfy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsbbgmd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsnbczp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bohyhzau.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkgdjf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyiluhr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ocftbnrr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtumtly.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfirdnx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klipkzvy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdiphzk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrngyes.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zndxlmkn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsoehxz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcggrtz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjnssmy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnxlyms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgkdzrd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eupkqtwa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptztkchm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wafwjnhf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2maawlaen.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqahmera.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqjdjhf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbekolb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2opehymvj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eomnztxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdscfeik.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpfbbvh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsixantt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjouwgt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgwkfhj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxhkotc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfccsgo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mzofnezf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhgxkas.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtgtcor.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hobhxusb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjxrrsr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkcyovz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbvsequ.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axzgnpav.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuhxqjw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpbgwhw.html


<!-- 参考信息 -->