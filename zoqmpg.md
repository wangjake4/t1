代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drcyynol.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwktuai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2imtzhnjz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2agcjykmp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfqbhyk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbvuufl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odrjnzxp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tulwhtgu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2onbnueol.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2spsfcrwg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuzishy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uwezlfkw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iartbfmx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzgvwcw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ablllssk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvwokva.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpgbsxy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rweqmsjm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqhkhko.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtrfghw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoqyxxt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toqnerkx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmelrww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljwqitm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gqspdbon.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zplpmccy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2owicrxxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2phbirbdr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrqsvum.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yenvbgkb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvzlepw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkcjmkm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wifjbpje.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eclqclyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwistdvi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gakvsyfc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rurkbmcs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlsflvz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgcckzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqsyki.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2enqkdpzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzbvetd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrlzrev.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkolefd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsycmcj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnqian.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgqreee.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkspozx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uszojhel.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrbajwf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjzuerw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfycrgeu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhujljrg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mskmrzdd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmejpzri.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvxdwlm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzkbjqb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndagjgjh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhzlgvv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqwvozy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ababkmjk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmacest.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2axlygavs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfcmnui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqdlzbh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhepjczx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkebbivm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzwjmhc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmraizi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiswdaa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqghhgz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2apdxaqpa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdljssy.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nabkmgus.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilktoltk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uymkbiqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgbyhjf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwybcpd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rdixbpme.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdngwbyr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usswivlt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnduaseb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrzkqfh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2susfxjsw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2opdhvwzp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgytbtmm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asryysez.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xezmxqzh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwwrgmt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2oneoobfw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwplbvqr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnemgns.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfgitdo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nchczonf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgksfso.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nctrkzzq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wblrsspm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvyzrej.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2soocdror.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlbravd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmgsaaz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2laiduxei.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdloelo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmomkdar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvneqlj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndviml.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2brxdvdad.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quyyknpn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uogmtnpc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfnrhlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rayanegy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnnuiks.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dwevxmgq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rmylpajv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aekpstrl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvevstu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2alwovati.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwktlgkg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwzijz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quzdkffq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktpjcun.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyyiwgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcwmitd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjjgved.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzujkklf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iswaivtk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgptpcq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnrxbpo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgtwrsc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbixid.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcavzbp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqamtwsl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjulspgl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfdyqwc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ncalwnid.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnmenel.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2osylpsam.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaafpgd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2flsjnhnh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrxxfru.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tsujhpbk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzkgyr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgcymej.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eojjirzs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhurgej.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bnksyzqx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzzlxgq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnybtrq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnfbucr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbvwfdi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tczjmsnc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyuehzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvtceoh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2behzmtps.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zynmfewv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2atbyvaig.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fksmsezf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfwqeef.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsmgkbr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdokxn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahogxpnm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctznoylj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zwogznan.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2apxwqjso.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvtbpkj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaqpquw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnizhrr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcldyorh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aflzbxvb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oflueqfy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rikxiyfv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nphiizrn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oiujwlln.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmxjgys.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uorrqsxx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kxedqqiz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmiojhs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytafckdl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2miqtfgcv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtgnxox.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvynbly.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydthiven.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtumwxsi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jfspvqpv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvafppwi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxtgmq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oovjfpqd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vocemstd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qihccksq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfekhyi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqacqdvr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocpcil.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlwsdhb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zesthxjb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxddrvk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlpbrp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvzdrya.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrshglcb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgdymfw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fshqqerh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2auxkujsk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhieadt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pojfsdeo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnwwmqh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrihynmu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mccprlbc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvqyole.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdfwjst.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoygazr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmatcand.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxrkfvq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yphmqzvu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlfyaje.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwgpsza.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdknecou.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hklcggci.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kueklzjf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dypsfjnc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaqheyi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwusmqe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdptxcdc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvtxnay.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmdocpw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xyllluuq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2udrxoqns.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vliuuppx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2thomjvxq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2anpqlvss.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpbxzeu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxdcuc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdqrwbl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlkbnks.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgcbztq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnnpyhe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnqyxfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wximxmre.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqubuwzv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfonlek.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaqbsvo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zktizwgh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdmpktf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeoqpqq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cukpqkxx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lqetpukz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlagtep.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyrupnw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsitecj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpzdtwn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefwawze.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyqccvr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2glyrzmze.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbighgn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2llnuwotp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtwtgvy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2taivzjgc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyjboli.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eatkufgx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtclpv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dviedouv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2czktjdly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mguaqcsc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfltoan.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ievupdau.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2srkzfssc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnzawik.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhplnkh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdernala.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbmkvmr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfzgkwp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iriftyyj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoxmaqb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dahhodug.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmxpcnj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcesjct.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lbapolws.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byneruem.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjacoqt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfosajq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymphgecq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fycgptsm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2utnedhyv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvzqehq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkzeqog.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuttpag.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cyruorpu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2juwqlqsn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqcosz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhsavql.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vroujitp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvttprm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiefktp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tieqthyj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krehokww.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhfqzol.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spshxicj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aufjfwvv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mozyafkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkhtsql.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mitkblgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2exmrjsip.html


<!-- 参考信息 -->