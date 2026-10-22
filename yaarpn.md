代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glwuuddr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxfqzxs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxvvpcr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrsduqo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkmjnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sblitida.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyjegru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzegxuz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cokuochq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgysfrj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ertyfekj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sosnspgp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybztqorl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkjjhwf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyumhsj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2djivzlpq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvfvgba.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbpihpd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amxmdtih.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2niwjyyks.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqkonsf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszofqax.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kwowrlqg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znbimign.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydmzbsa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwjqbxy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2minosawg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbmqwbc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjcimpn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmexgw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jddddxdl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylmmgw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidlrxwr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qawmejqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcyjmmu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtwojna.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hudbjdga.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksclpefp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlarjmng.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlkqbpj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiiqhdz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprldukq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jylnyqtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dysbgwsg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbldzmx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ggasbpuj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rorxpsol.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnwgtvv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpmphlz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhiwdcq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtgrxnf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grrcfwsx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imypbnqi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djdjshim.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqqbgm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbtygqc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiaaeta.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzcckqf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjzlwan.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrhokqi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2andfqnue.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhweszv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbthfdat.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqdqwib.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxcoohx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dliqdetg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yylrkbhu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnrdtto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkqkrkl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoprzhg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hegudlqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drncbxxs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdxvigv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpncksvk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gouucjvz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wggzoygq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cipjqzmw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ntalppdn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrjjelf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dartvmta.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xeujhutq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqsukxh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuhxtyr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bboaqqbs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhxbqex.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaqyltu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfzdizs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aluvscll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrocjsq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2blclfehg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2locwtdax.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esbtnitr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2axufsvyb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrctbfgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irqaekyw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaejqky.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bmubtrhx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2chujudjg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2igehmowk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnecio.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bazhkbkm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdprnxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkvurqm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2khxuzitc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brsqeryp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdcuumd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzcuvan.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzaxfnw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lakcfwrj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjttiur.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiijawe.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2flaydruv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngizkuow.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mnztlsag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vuillpgs.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsiatvn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvczhncj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qihyfmwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uivuylqd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxewex.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uazhuhow.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgpghrc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2buhybzoy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khpwucde.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydljhchb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2skdrjokm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsohvzlg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sbliiipo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmawuukx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgskyess.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzivbfgy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfwoscy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2haappdmn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2viaolqkf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdeybqb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mopbzmrt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgdhlie.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyqvzqx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidvihb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzynxaa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceryudec.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbxfmzk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzyytge.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdggpx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwiqknc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kracgpll.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ehocftfo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbqzmhf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gialgvtf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2apzbbrte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcimlaz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2beniyhlp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhykait.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zscpfapj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwraear.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tkladkwo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hafvxpan.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkeycj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qczmyear.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bktokapi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjcwglt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dcghcgbd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoejoqv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuuihhl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhkjjdx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2azjnzfgk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbghts.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxbhxzv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xohzbobg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mptqetoe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lyekcsww.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qypbirac.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lljwancy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2otrvkcoz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaaphjq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azsjojem.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nnarwxzs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobokek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzmmwpr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtqpvsj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbqukvm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bakejseo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmyryip.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tzliovnn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dfidckyj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbwkzvn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwzwatr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqupwlw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoucxwv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlohpul.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsjvipc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2notzdojp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqagediz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzpdhlr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2titkozri.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ylobzmgq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twxlyhzs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwoatjq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkgxmcy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iolzmzss.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uavpnegw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neimfuvt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgsrisq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnyiba.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bodekdup.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpfwcbf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzxkcrq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pocjmatv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdxjvpf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkddiqj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2naxivqae.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyilxxp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxgscca.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqgutlb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwepzbw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdncsoxd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hurzmrwc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfrnazs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2erlhsrnm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnlvxht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bereiolt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2axpokqej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjuckzg.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2evtifvvm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmrnkop.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdoagib.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eznrlnia.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smwhwhpt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxlfjz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjephtmh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnuyias.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hvghzakp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjtnlvd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fccvpkpj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbcedxg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczabrf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgrijcr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrvhkwr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fejimgwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfilbmen.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lnahecdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djxtlgps.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dplhtied.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhvsmov.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpcqldw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2znzttika.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxnqovo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uygciwqy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgktxpc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjyhatp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxmzuzg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmrpntu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjticbc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkffuzak.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqvydad.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yneeszby.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvryxh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2enquytqd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhxbhc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsafxco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfejwld.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwnqntd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2opiybtsy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjreqfsi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2edjwqdhv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrsovud.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvrexfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfeyjqc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdlpsft.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jinmisri.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2egvitfys.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaovjnf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrycsvi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aviqtvdl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsyuip.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qeklwxrs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlveuxh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uduvbtbh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgygnng.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjubxgdn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixweaydi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iohznlqn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lstmqwis.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eimsvtts.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbtuhke.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qtadlaoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxozntr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fizoukpz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kecyxwot.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlvowhx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2urxsfjzn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xmptweuz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtjthsn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrvwlyw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bibocxon.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhzcuys.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrqclvn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fckdksna.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbcttgx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvqmbj.html


<!-- 参考信息 -->