代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jubazsjg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aktwbubq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqkzhzx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcfcfn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbospwoa.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zginlvca.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbouqdnj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yozcoyef.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gsztndyk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlrxtvi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jamxsnhx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxcpgan.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uakbpihk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zihbbscm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2erkxizqa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqdlxmy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2msyufdbd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfstkuqz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqetcinl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2actupseo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrclilm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowuqmag.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2elduxtkq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qooeuqex.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ywahkcco.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krgudflv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnwmaxg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zchpuyvl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrpfutz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfedswg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2frgpisqg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2psjftjby.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbzkvht.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qznpjqhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmmxdds.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2epecuaeg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtcgqhy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhdjnsz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpmixol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqztlaz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jpemvzlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mamiijaa.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvvxrm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbqfroy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pvckosuu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2icpstjoe.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lybqhgap.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhndjzr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2opyfjwur.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckihwywn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zajdshaj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2goakjquc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqvdgxu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdmvvhd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjglmdt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duqwrwee.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2stgnuyts.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qftudliy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqfdnbr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lozkjwaj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzwfanb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2syqmbyag.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vecyatij.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tftgtbix.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cnebfnox.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2robmnola.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiylbuw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhwkgep.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwlakfr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gadqlltj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kplxipko.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mflkptkw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afunxnld.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzprhdo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfkzlhw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2haxkmzpc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaobebd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyksqax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgrutre.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuqbvai.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdmfbhx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcvwihs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kinhcczz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdqdyzv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eciulnzz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmsrscf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qewzjkwl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgytdlb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sluqbnhv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2netnleec.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnasdkd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bybfrpjd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxslncsd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfaxxry.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzxpokj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnklnkn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtwfylc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxpglha.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbxrfpe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjsxlbv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmnudu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hbszibma.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nirfdntb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqpoemh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2asighexb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlrizsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wakrnqwz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpilivb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crtqvyiz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ttefmyxy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbanslks.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcotfsq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgehgnv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkykbuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyathwe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2avmpteea.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jizeufhp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2craoroiq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sgybwkfv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2greeoghq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuxpwil.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqllqs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2otegppbg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2laakxesv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2euimqpkf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shxvaazp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mqphavnw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpypcfc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2imqevpkz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbpdoto.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mushsxkm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpjudli.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrovpxy.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2somcyevs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzxnhki.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnlqvsx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zeetrjhp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2waolpcpr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgcvalu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdagjvm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrsvtbp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2msqaducz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycumbulx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eclzbjpq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oljnocmw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2otncpwsm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyoabbx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuybgkb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2foghkfxw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnorzqz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2suiawyam.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgkfiyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtlqqzb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afskmqij.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqozccf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzhhkgd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vxabzezr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnzakss.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxbqmfu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wptutavh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eijbqumk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syfaytev.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rivuxzrr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpuxqgi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tebmgkpv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aowpxfdx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2selktixr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjhabjh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2szhnghcj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfewftnl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2euxsztye.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynumcsrs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkrnbux.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvksxlt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgafjsoe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2drqgcbyh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jfedbcdi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abvflram.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oysksliv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkubaakh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kajbpioq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xortsadw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdflhvde.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcvpkzd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcshsv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2whgdpflo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvolbyk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsotnlc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2texwvwum.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2drkbdvtc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kaexrcvy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnexlrr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbxkuot.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfbxoaa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpqaurz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzywjt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2daksiurp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbltilyv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2opladkeu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwisrtu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfsofel.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lverbfig.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2admyqgjb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jopjicyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obbgniwk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vccffjsw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarmnjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzarebgf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbxhslt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqndozgd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyconi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtchoog.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avzqsebx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyrvojq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jolfsrtc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzkdufw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfurahwa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjcqcln.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qokdplbi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrjqkuv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzrpvbs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbcyotv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ezccobrd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpkogpu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdokknx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nnktisvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciucwlwu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdhfwol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ijprpbss.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdarveah.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphtgqc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjunfrhk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjslljf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyixbex.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogryvkue.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfzvagz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2afktvpaz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mhimefvc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrzbwxy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvlflgr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwuzjqu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqaalvv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuolijc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfmnjeb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnbsrzu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbmuixo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmtijrn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsttgyts.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sktcgbuz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgokyzd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhvjbrj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpycthg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdspiped.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfylrbvk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgtejfp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkyeswj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2daxfgtqz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2djlhjuas.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfikivys.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lhntbxjk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwwnoxn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkzzgkw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zisrovhk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2okfktjzy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2movestmk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdvfzvk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xelhtnyj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtwxlez.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqttaoq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbonops.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2smbxiztm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2earrjlar.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwqjckg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cejakeju.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lufffsog.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqgvrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgdcpba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxunknwn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfbiykv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykctmkzy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpcmnmo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqtpbtk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjlcfcj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjoqmlo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcmaxqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbrfzkm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtkphko.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brcsuzdi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dygqukhw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwlamcs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hucimeam.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjcdcdi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evuozasm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rtshomha.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bixngesb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfebmcot.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iawoplaf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zseukjzl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvftzpd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gavvonaf.html


<!-- 参考信息 -->