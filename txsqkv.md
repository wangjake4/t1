代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2thtqrqyy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pntrfwkw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yszfykfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2orlrzvei.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsgifbe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2svopnumu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hiclajkz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eldaypkw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlyupyb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoputhn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tcahqghy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bcidaxke.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlajcfae.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjxqisc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2obwzpjgu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkjysrh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapetekk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dwueeunn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmlzccc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2smtjfape.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kgblfbgr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfabmhh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xalyesxh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaewjyc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yygxygct.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lynqxnbi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxgprte.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfamxnz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2exqsqqyc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cagfecge.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcsvkfl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ninhcuzu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hswgyuvl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvrosve.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtuzdvj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddobuth.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovosaxzt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxixqbv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtfxidi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklrsmwm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaqpwbw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpscyvf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrdwnsh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfhaddr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuspivn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ondaqgao.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmpbrcz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2paffogix.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fshictam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsdnlkv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlrsqzb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhpqbnr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kepbnofx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eoebpsjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvvrdax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbhgbqi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hxszsxch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofirfzpu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2egthdzjm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzybcqz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2njlxktxm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kubufcyp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtjusjn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kryfjhuf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrkdrkl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdteeuf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlazlja.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfzijda.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvibaga.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pimvmpwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iooksqiq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hflkxldy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yyepenpg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqmbnmd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmdamkt.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvicxyi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjewdxo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtpplss.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2caslikzf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2etiebonr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwexioj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwybwqh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcohgjyx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2opsmpnkd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwlrczx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aueerwhy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fopzsskg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdxewkb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czyvayxe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2seqabjov.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvxloav.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqiyhkb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmnxwe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvykmgt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svxgcmax.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuiwthv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrelxpqj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmdmpxr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxkvwum.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvrxylj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uehmgzfo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzwaxim.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmrspji.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enryktlg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxjbpl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qesyohzx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzdebip.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gakvdlrs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ighwgnym.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnccmzf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ampoaghp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fewtmniy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txtojiem.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2purcjdej.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dufpyxif.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrqmatk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2biidyszy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2facgpmoa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zbygqhfc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xalnjvnn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2inhjjowy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnnhgkz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvzdkme.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcrohiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scagmydr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2atjdhzys.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biomdpfo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xfycuzwk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgtvumm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2obdsxjbb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxlsrse.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bduuuhob.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2feczfabi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuxrgli.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvqgyir.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smnztbne.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejptzcvk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgkyblz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jqohkcxk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwbbaka.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmnlqos.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqapoklb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkkwdtb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvockzst.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnrckba.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqmift.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuatniae.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jaghvxoq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lipkiwvx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qacegzfa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpsopgt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiuievq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tdswcadg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqeuizg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xokyillv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhgwick.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yolaodcc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2izemoitf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyycickd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsiwgci.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zwleovqv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tchiicyt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfnxhxi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxocyzo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmfvrct.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ommjxceo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoeouvb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuqefqi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtxoeaw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxkgjou.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdwgnoa.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ansbisof.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnfxnkl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lukmtyuf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2boijhpne.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtarvue.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kudrrajh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoyjfdy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tgycmceg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mzourntz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsqmcwu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gealvjhk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxlbckl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bpavqmfp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpsjaob.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxwbne.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhlbrh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjxwalw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrvksks.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzoogyb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqkcbtz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxywibw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzjryok.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2edzjkdha.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxzrgem.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2akmqqomo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyzvgtu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrkvdeh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mufckfuv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmkytem.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2czmaovho.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvewmgf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2umhxztyo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bjccdhar.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eugkfqca.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2alhpfahm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmbwjrw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yzujzhbk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yxepxqec.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2skgmvqce.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bduorfiw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shduuljs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvnlxpr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vareirae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfyzugc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2txfnjshj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2szsvattc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfqlhjx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzouymp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2naxseayf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isucxpxh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hivcnraz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfxonfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axmnwozl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrpcxkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqonffu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2njtoaqxo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vldzkbpx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbdokuk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwnzbax.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2knocfmax.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhgjvyl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxqnovt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmewpjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aivizktt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2basdtbnc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erybphql.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvejhhw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdsyzrp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rvptfhus.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqdgzxj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjresyt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrvljsn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xoimdktt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfsxnzy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjszofm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxwukfn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djmapzxg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnayhszg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrsagvb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdnhxsc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmwbmvj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrmrdlw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbjtfuf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxibmgld.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzryevs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aiszduin.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuefiqjj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzuqxat.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhklsvq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgeudnd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfjxevm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2raewghjc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjnahod.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrgdkxc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbnljkk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmrkflw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadsfta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2omucojex.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tzekknsg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2paqlrfts.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2brvcnjnd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2etiejelq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkcnhvp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cicxqqrt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vitzetbg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2slyoezzw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgmokfe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqdjal.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoyijio.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlzudzq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzreoygb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxdbtcb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbucemb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtixftkg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfcmusd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjexoesg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qostcifa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsmjlab.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaoroob.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2brzpvinu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sywdsllj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2swsprfge.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykmohhf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmwtlhf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzblyfyg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkofhzj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyqdfqr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uhchuhhj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjweeww.html


<!-- 参考信息 -->