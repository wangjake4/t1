代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2drwjqihs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqunyagk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkryar.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyrgxot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fymqnhsu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2taafwwxp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhlljtp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uziswzxr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgevbfy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oetnfbhp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhirrykw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwttdln.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yzicytpr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnmspnj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjpauyz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuzjgms.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdwiavr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ejemivky.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwrmgmm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtlasmb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubiriw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2auaondwj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkhysew.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfogqyxm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pexekstz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2atgrrmzw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyxiyhe.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaidjyl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmosva.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfhvxhu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2evxvxalj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2phraldlo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxcklnu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iyumysxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnlgshh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzcvclm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yscoxpvm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvnqboo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzdiaat.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xneicazh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cagiisjv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2byitcnoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgwvvev.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzaroqg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhwhtdb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2seokhknm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdzngnr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kxotkidy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2owyymvat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tasjveoq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlbuqmu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxchzbh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2upydxcqs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcujyhe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdqatio.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlojxypd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikfpdx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urboowlc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2njafxfrm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqovtpoe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtjlupr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndozhgtv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2snmuzhis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpokibi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xpagbxpg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lyixezkn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chlfwuxc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmddemni.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkknzliv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyqoozz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mojafaqw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aivcbagt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpzlufn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pawxbjbo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvuazro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iectpvet.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eplqtnpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxggqzo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcgebyv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mvilpith.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2khtguewj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcqsbyu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeubjxyg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiabkzb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlyepyp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpxikyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cchgyjoc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zibssogb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbpbhvi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drgsftgw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiidxwgj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlpjpzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2spnahwsw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyjzevc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvsoogj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iopdrmpz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyurfjp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzllibe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbcfckp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuffjev.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yfageveb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2neqasqtf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gctpzlhq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdrreng.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bxieugbb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akueiujp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2koqppbvv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtdqehg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmkdvkq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pubkvgba.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfihgetl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2terqtfde.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akeodaxe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbfttds.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsyyyec.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcexqz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kayecenb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqenldml.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exelszfq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sptjjfhr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tchrnmpv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjqbaxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuyldml.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2alkqcmol.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foarzdfv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrztqse.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asodhldv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjszjysf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzccazx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmgbsml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfpbmim.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ldusycwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvpqqad.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdbzxom.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqmqzgf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuuhbkg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsgvdyl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwlryh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bohfwzxf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eztbrlzm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwehyzat.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjakhxix.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxvqttk.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lonmmoqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpselii.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvvtvea.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkopsvw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrjelur.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjxglhg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtewwdf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuenmgz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hinrwslm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gevluqcs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyobvpfg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2thvithlp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjdxoyh.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdermjyz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oivdonan.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnsldsb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iparpezs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkezownd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzxehuq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgrjcty.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spqhitix.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fevkqjgr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uawufvrg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lomelmfw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itjmicnz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hprcfbfg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2snnkqvip.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2odwxmexi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjnslep.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuyesmm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nxowxmnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tkngvviz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sldluojp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2laxmewyh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbimnxk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxljsere.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgesxne.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdmeuko.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2isknojjg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmksemxl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhfpnyb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzrcugq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcsdiet.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbdiuwb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjfelrd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhnpbhg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szbevzvq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpregxi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zznuxkit.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cshhkqss.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kungvdsa.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uibbtcya.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hndfaxvc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrxyfxc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjscgncn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pwshkqtc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kpquondy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gaahmxwm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcbfgia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcbmbte.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzasclzb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdcareo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otzsrqsc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqyvhdm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdikfka.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzgelun.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhscroj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoprqbex.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuvuadc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2temrkyjf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2igcxfmdi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbduiiyy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cowsiacz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2skflghvg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztejjrvl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqasszhv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnuteqt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2htylwpgs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gztxgozs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmrlwvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmjnjxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sneetybj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lseygmuj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjqpbsf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcpilct.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrlvrzf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eclcggaw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eskqebdl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfstync.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgioakep.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvdqquk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmhfqyj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbvephu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjkpidr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oeghlbsg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmpgfb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oynjyzpr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixhihp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgkanuk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2svceigoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtmyfhc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2malqxiop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvqfqqk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtxvwyf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzjemqq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnrllpb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tggimvki.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2caetsvpq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnlinip.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvharnje.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kserchhm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcerukmg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiijpps.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhavysk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jiddpenw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrhoiod.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxafiva.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rymltnsh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhbloeu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxduptx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlbdgud.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxtyaxx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxqdclq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejikmqgg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uehjqrlz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcjyrjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacigllc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uatptitx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmlelbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2henkijzs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csvpyrwx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyuqodu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ketrkvle.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2myoqotmi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysufowui.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jocxlxap.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhqmmcf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmwcjav.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxeikzp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2woxvqaos.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqgqjld.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gizcnase.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dialysop.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpklhbo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gllfaxmo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2srtworzf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tilyekgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcsbvpv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ynclspzc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwgqmjw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwimrqv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtapkbgv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2whikrcns.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxmxxcr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxxjhvm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavcwxgw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fspclkwd.html


<!-- 参考信息 -->