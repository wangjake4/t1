代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyapbwl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wfozbrtw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scvsmyuh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgdwrbr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2higfcllb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqpkxna.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqyrygu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fleybhfz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kltuihrn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnibmwsd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2euoxuhiw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzduebhr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlebxbej.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxpjitp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rebfmeot.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpvkbkv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jijlqeuq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrirryf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgtbnpz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yptbvnlx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcmcupb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurllwr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2duvsnowz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwsofqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkpuquv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmoksuj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiumtstv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hufzskes.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxegfqr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgitkwuw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxkrrne.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqvmorn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoixlfh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpjddsh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2momkddzf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nqybfnkn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ffenufxr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oackzqpa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuhoosz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnxjfza.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sazmijxw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrylhpp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exovtnmw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uafogzui.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtodofl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylfadyp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgeggex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwfyhtj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2virghcwd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzuyukf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyysoffz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimwppvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvejpig.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrgjejz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpfzlc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vefzpech.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxniofl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsmndhq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxsxdyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biivxfju.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnoxbgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voimurli.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyyocnt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgqlbdl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dayehydy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjghgxn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyifxwgq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2misdhxoz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xqowhksc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuggpvpl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzlxgzy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdtwhrt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqkgept.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxtqqfp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhcaxm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmqhrht.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nntiwbgu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jruktmaj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuagwfg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrqdeln.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuotmfe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccvdiq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2opvjgscs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpyvocr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2exgzutbm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxlgzvm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbalyjo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwfeyfp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2flphmsmg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwebqixl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbascaia.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lekcppvk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhmottn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkzktze.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwkracs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvdsiwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akfzjhvg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nppgyrzq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ongmakgd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvgoeis.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmxigmh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmeyfkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyfqoop.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qavewjnt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qowruhow.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zocfpxzf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbfbldx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmbtmre.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxbadvm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyehirj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npiqmpss.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imkanveg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uibhodmx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbqqrbu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrfpzpl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdayrjx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfunxvy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lskaqmrq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2perueupu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoqukhk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwognuxw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nitsvtgf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgdvymr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdyibvu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkqtlpi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlqtlna.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2llitsbxh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltznfrwy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdkuyw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsxiook.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luosenbp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2srnaqeng.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2apenrhgw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkztqfta.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cebkexfb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xohujrus.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikleuzom.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uacyjfji.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtwikp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgjhvce.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2outipmgy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sldfvqiw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cjayblgx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2faziwgwl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmverwm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoaklgq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vquadbij.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2armnikww.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2koypznyd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rveuevik.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbmhbmg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvakckn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rynzkfhg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2znkbceuc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oengmlcc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzzqegf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqddudz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vorzwmja.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoxbdzf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwboajd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaqxuiw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucetfdgz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wngjrnkf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yohsulfn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxwtkqy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiysvxg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phxwjukz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvgxjnv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bpckyrpb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuuzjda.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uedymghw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wptkkkpm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cmissgvd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twgyrlnc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwourqfs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwiqlii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qxulkkne.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wdizblar.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvycqlq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnolkyh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnbiswo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrwrhgd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cjovpuhp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dftlyklm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaopnpz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2peojkarl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwiefbp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jshhepkw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkhwphx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blfhatna.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarwkrh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgxhukn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hqanvkng.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dpacavph.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqufgfq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbtdgqv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hodqhfby.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkflglx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ayartmeh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfnseiw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kjelkeap.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2irqldbcn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvrlptf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2usnwbkts.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ynetrboy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2terjgcnh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfnyqsx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwhwrvw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbshdsde.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tbphdrjj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czwrhylu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpdvhew.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyiivpz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mghrztjr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfdxsb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtgmvhv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxivcsk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gywsjhkx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cbocwfcq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmplinj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnbyegy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2upyzgxpz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azbigclt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqixgzx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mupnepki.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvtkqnr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvykaim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqrvjzs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrkzkoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jijbtizj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoakfix.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2anklferc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmssowd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfmlter.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzxqdfj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xliqorfp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwjlenm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvgzmpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqezdzi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeiyhsl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2clppowra.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opykodvh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oeesxgcm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2loboyofv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaeplgi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwlhmbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2opywdlte.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pumcecsc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qwajweme.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoyzoyi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2unvmxhdo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzxqvhu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrerouv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapplood.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqzzqod.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtznpmj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2airfbptk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2momymfzx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zulcqedj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rqijbyeu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptalhlgm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxfilvu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuhurzf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2joloitwi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qavqsvno.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2agroonlg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rutbnaju.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtscofb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkbfzvc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyihcmw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gckuuarl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wbozvdjd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawaxtb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tnetfdsr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2owuhpexo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fqawgfct.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhskkmn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpbnovc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwnspvg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyhfkyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfhwwlk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oorvhktt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlapoxl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sixttsgp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfecxccd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmxlbjt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxjxkzr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxsxmhk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkephbhp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnwnqlh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksorxcmp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2euaamabe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaumzic.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmioua.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2paoceveu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqcrbjq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkbqwl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpxuatn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idrexmap.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2flpyzghg.html


<!-- 参考信息 -->