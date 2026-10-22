代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqzckp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngdtykh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfpluhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvusyqgj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2piskhetq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpqbyta.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exhleuay.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxzkeyv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcevzcpk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdettqo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hedqficd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kanafxrx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxdcwlu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywneqic.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uouvuigx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hflkhuwo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiitsaud.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jqusnnwt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsttaui.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbwpxnq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icrqxgfn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqugxal.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzmpzpr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wddrzjfm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbaymqo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ajriyrix.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuewzfd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tinzlhyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zktpnopw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wuieuiyf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmzdzhw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aruuviaj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqovrk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2useytwda.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqcbzhn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eoajtavs.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkobolc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwaguht.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2invboife.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kfklntqz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbcknl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rafopufy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twpgjdkz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmtuqam.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ropvshly.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kewsyrah.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzcendf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2geaqrdpt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2inyogtzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgaxomg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zthfzcse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbavgui.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgxilkw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mafecsgz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vooiqohm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvdkmei.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqpolcw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgqqdua.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvcwtr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfjssqr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvhsflr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2psjvpvbq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2clckwobb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyegmsfg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nwimgmlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcgeeab.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdvrvnn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbufqqk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sylksewd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpbqzxi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kocihrjv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlskclx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnrxart.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzauqvf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvrmaqk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbsgblq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpibyxg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbgqpnc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lweelcov.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpekbzpw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhsiii.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzuiolq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yswmvmat.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvesewsb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2izycsqdt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmpazpm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kosmkcgn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqqvqcl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrqtfr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzmkry.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqgvuhx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdstuwal.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pmblsehu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vflykhge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ursjumzm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aimnsqyl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uesjibru.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiiedlx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhbttji.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdnnayj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eluibtgt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxgkozw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgnfeuu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2giljixwz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxrbjqy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpwhiru.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrzzzfr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdjwvms.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2futrifuf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpfrpnu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsxfomk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xqejomac.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsguuwml.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzrpmpi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyffmhwh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzrqao.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfoyrvv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmrcnrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvqhhit.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyujfxk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcopqcc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mozumiyu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjeshpb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoakvia.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceafuxjg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcqgzgg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vywfadrp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzttyswz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpiiklw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnmwbvb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlspwzay.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kghpbrwl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhgbbhb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjmuxei.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhblydpk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qxprjtlz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iauobwmu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkglsklr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2atixjvxf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2olczfbve.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgolzdj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcajowgl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyehont.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwowtgp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzitye.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsznxvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqqpmsj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzynnhh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2csfuggtz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2quueanla.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yxthwbqq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhfrmjj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsmurkg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgvxvsw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cssfakmb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rexzqeks.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsqeoni.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fwojjqka.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuywksc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jwutiaxr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rliwtlum.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaeeoig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxwnhvi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqyxofq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqibqbl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hoidoays.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrqmssp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qouyjhrh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2texkbjfc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2boklyqri.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwzlvxb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaothoi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkszwf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsljlvpe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjtetu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2avjkdqxv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbmunej.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqyevei.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqsnxiv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsvtocn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrwukbd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2krqfisgy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyuaxly.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fanqadcm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqodpoj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adwjoeiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kfggsblz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hqanoctc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kalkfkeo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aumwrjtk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2okotkrif.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2apwwtvtj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzcrfn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsbzyad.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jyunudrv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjvhule.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlbvvcl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyywcrj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgucbgo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjhbzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lidufetx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnupddu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kzosetlx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzagrbzk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2llyaugji.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2saogzirp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdntiwh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoyuuka.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2otkyladk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwikyns.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnnaijo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvzjsjq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ditazfab.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uuslxejx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vynagmzz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2toazqyco.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sulcxhcn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjbqvtk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2upjwpbyp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zizuubmu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbibgyfv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvaydpd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrjfoaa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwalsgt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwaquse.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2evgkrxtx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utetzczv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcoejju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooantyly.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gecsrprv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyiwssm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcvcqip.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xxilbxuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icailqcg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuyfnis.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtfjeth.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjlcpxb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbhorgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcfdzkl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzraorcx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhnrmqc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcwzxzf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjafdef.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwhirse.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnnbhf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrqyjcv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zjihozmh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsnxzmy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwhgef.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2igyxjitq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxchbgbx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhxrysf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2taeozzhb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjcblgz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tezvevel.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxfgila.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fybfrqrq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpuvflb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyjfuxa.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozyyvr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjzdmkg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcszsfs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptywuycx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmubwxm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2slmcxwjw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwosfax.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmqoler.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dymmtjvy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fykyuhhz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdwrrbv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrfcbfn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqobaddo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxumtjqk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djrsqpqs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iygconlm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcehsuo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2graatgxo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwawhua.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdqocao.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjdmlzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxreznk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdassgye.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yughlqhe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwzqdcq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rscqgtdc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtsqaeh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefysoqu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxlsgnd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2utjifwjl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaxochn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqrplqx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gakxoayn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupxujri.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxiqxne.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozcqnk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vmorytyp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kcormwgr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqkygbi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcesyxj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kffuixra.html


<!-- 参考信息 -->