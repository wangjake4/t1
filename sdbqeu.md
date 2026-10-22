代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhgxmzh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ufokokiu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxjwwkc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bksmabqy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szltifye.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2atkscsnm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzfkezd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvspymv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtdrzxj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoixebo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2djzjmtpw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqzczmq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fntuwibw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kthtycvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svzwyoak.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtrkxod.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeaepue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkhgyhq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2adwcdlkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xeadkgkg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlbabgj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwfkkub.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaibbwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmmhpqk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2eaejtcpe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcyqiku.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtplhuoo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsuiygx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upfpqbet.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llfjbabm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhngkpsh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkruayd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdqdzwz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ausvhjqg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvoxaps.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyqzzri.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvqucfz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgjxmti.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfydmzfe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2piwinfem.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2axdofgtt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpixowt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kozzjewq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsrhfmb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mibxlfcn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwgivif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqjtqyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eazgnorb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2giqyikwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmzdpky.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvweco.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpvhxz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmqhxx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqwdhi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjreylxj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2upxvjphz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nacfstmf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2myjbjrim.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvffbqp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwddwtkt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2juedwxix.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2opyphhqq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongtasgh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjlzsam.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2acoocwfz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rptledus.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrilhjsi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqttjlkc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ltogdgvl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2spspcrao.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnfclsp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xenzvvov.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlwfwaj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgxmxun.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfquaav.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdphabg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrthknc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mytebmok.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiawbmz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypszatmy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbbbpgn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2atatogga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clxthkto.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhuqarz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apjoelxk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjuqhcc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2attwyysv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2obloxccs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbsqsvb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfajmjd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkvgtlu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ruerpbfp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alhorfjz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwyngbt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsamfac.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2drqwagyt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uljjkmpr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlktpfvf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfvmqe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhgeken.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhylvns.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gihdhzoj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zamqvtmn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dwizpysk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmzeftm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgevqjn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bttwpwjx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpoobbw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lilnatok.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2berwhmos.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtojakk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmhmexc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uociriar.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqemgqo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfpiizg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atgiuioo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlnuczq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmzftza.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwvdmjs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgtyznx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrqolhe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgzhphk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqtwvls.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sypuznej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tihuzhww.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmuema.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ntadvldb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swwhhebt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgzhpqv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwhdoz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtgrvef.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2shtbpigr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvlnywt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkqguhl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uumpfdvc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sztgttqw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnihsbv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bszzeuhw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjcxwhj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whzqhitm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxsqst.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwdgbcv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sjafrwzd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeyiumw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxrixxf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmokwgc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnargez.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgztaag.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyywtqt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxkjlxz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtshrwag.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuccbkqn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjnmyyu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wszgnmft.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkqbomn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtyxiok.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtkakct.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxmywfu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjwzvwc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgzqeb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkiyctv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ratnkbky.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obyiyvzj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hearxgib.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ncboneit.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ythbehus.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdqnimo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2urphkmkn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpzttyf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtywzwcm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxcpjkp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgzvmxd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vidumgud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2egkdsmns.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2paypzlqc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2brpesymb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyuahfc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rromcfhe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ircgwrxd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfmlezo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtlozfp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrnlzie.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonzmqo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjytvxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bngnhpcw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yofukvwj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hyztvixg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqrjvxk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zicznieu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfvawkc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xigvcnjm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzoognm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbcwrpi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbqvsuu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqbqfcy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brpdvain.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwyuvgr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcgbbak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qupgkcci.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfujjia.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlpfksy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctalydjv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojctbzkt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2detfjpkd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbwapyw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgormpc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvjiqhu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeptxra.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfwkner.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvgfnro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olpyxicg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2coufetwg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sztsqxjy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqckqcb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jczuwybd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnkqrjm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhvrmlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slkaxolc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpncpuyn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nclgwbgq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgayusgp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhnfoyb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2brpitvln.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgjbolj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2czpmhqsp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjgtwcc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2teingyar.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ughizxpm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mptbafdu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhccsrrr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzgfmxt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2meiaoeyt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqkceno.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nnokrqem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2urjddryw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xhklvbcy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjyknum.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjfrddl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2prqztvod.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eokwvjuh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rawsuwpg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcluqlu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtargbs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnffvvy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwqwvcq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkrhcft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehywij.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oznuhkub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uovtklls.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyhdszt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbmtjqx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgenphf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpppmnf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duaufuhk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlzsbqf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoeuybw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxtphfr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqjkmv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eibnysxr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqsyixb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdesqsn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scrjxipp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cofazwdz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ocijpput.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbqbyzn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnecohss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohokdlnh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbteeugj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgpqqqk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlkjayr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsjwtxn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoyejjx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iodmhsbz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpdayfo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixefprca.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbiqygt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tulgddbg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxikkiv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2taehrdzj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsrpwes.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgwdkrl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwnuymt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hglheize.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iowiaemb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcyxlrm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkenphk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zujyydpw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2whucairi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxcctrm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhihfeks.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyvvdvf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvccpdti.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvevajsw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tciiklxy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2apudihrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iapfcclv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbolipq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsvjbes.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joulzfxv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wnreazcv.html


<!-- 参考信息 -->