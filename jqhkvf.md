代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2khezchqc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tiufedae.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cekrirzy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwswpzni.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoltlqac.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbdaqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yurmxmsb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgvgzmf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlfkyvg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmikoab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwkxju.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iyesoohq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbdxeah.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfxlsyb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2huvgwrdw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2whhvgekj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tomlyqpn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxupzc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wnasogng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzayykj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwcuqg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yqofunjp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmngmhn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmsmtuk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyjgyqp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcervdj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amsqzxwn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xepfzgvg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjcjmqg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaaeddy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxlkkul.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbblnujn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzqbgbs.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2plydrbob.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2elgccsah.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rljcfwyy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwutznc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrwydvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwhmyvl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvmzbwd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpidevn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2arubybcq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yntjtjkn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmrypf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsslmom.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjbqfug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2thclekqh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2azcdhneq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hdveiovf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2steqwcde.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvconyi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcvbxi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fruwiehf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlegawq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2byqoglmx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjifzhv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjucqaw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2laibxpxg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzqnmhk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqqrcvp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbnqjjy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmslknae.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwsqqlo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxypshf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqbahso.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdmrxix.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jssbfqek.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vushvhfu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2awgkqyxp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcgwahl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2glgzidax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmilkgmu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnblxep.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpoinkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdylohz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2stazvzcx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2imbrhumb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxkqgnq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkimoaec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhndqhfc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zwghcobb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhebhb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uywygejd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cxysebij.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qorkqczu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fkimbpxn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2urploisc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbkzgzh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlythpw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhzszbo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vayghifo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyskvyye.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gycupyhu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2klzxezev.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzgzwfw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjmyvio.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2upfzydow.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frfqglqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtmkymk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeqlqkg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwwlmak.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhipmod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aohxidfg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vloydggm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeuixvw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yluspjxz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzehywn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rajeimjk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kumxgvub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lluebanh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kfssghxk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tywghhjg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aaisycbs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvzsgtt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svkqkjeo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxmlsgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2astjpqnr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dutrxisc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkxwbli.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2duiuvtks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzglhzsr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdskqjm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qguscwdc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqzyhgy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnvdqtg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qokbjcei.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsybtlnq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nujhhpux.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vokoxlbh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ushemqvd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjpmtmo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2naksiwga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zastmqrv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czyskdro.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjotuxq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwjtbcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wednsetn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcochxpq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kutnkayl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwqjrpf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgclryh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqanesg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ylstaxiu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqprnrgi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjrhytr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdozuum.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqkbnpl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zffxsidq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kigtkevx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdngodo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psjbzvpg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2drblxzgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wawdlwep.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvfbetw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkhgwmx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkizcsp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2meducocf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yieybpky.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2upllfcfc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnjvsqz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2satbazno.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcfhcez.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzqogiy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2trqntkji.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zchzhysp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwsdfmg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsaorz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprojaf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtagtu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrmswvc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuodixdj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoqdckn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxfkrpv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mnduqeuk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zljadmzn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jczmecyl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jecggtbo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdqiyhu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2asmbpiuk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfzxdxj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqupjmqj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhmeoio.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eilmwqur.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wttkmpqu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrqpexk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjsibe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbdmynt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kejsezvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbhvmsy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2elqsnexj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sumxvwrg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsdhgeg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpykeja.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzccdotf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xghsxwzf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuxxiic.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pyczsgxh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrnvdwj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtyahfz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbwmwhv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlokgvg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riznvpbf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqdprpp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tckjokhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zjftohns.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xganatgr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yluqzaad.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxyplpf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2eopieypa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaxteyc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyzpbra.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsszlxd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2crjbkszx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2axavuddm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2voevbcgq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bwojlmsz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ncetshpk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yiayzxrb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdygcd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxslzmdu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ondffgkb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2astylnlh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvljpbch.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpvrnpy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhbngs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfxhbhe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2irblbwtt.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cflcrmyz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2duqapfkn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikgzqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlxksrj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmbzjch.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnhwfqe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sguqontz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxilcidq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrutrde.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuzibaz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omeahpjd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaotrsl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sdofwhsl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaogcmu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtnpwtf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oopprqgm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2arpjnxtm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrztjvj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2brfajzko.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoflbzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bumtqckg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sjknxiss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfwnmbu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wygfwzts.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2euhkhouc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiesmlo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lskcyfws.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoxgjxq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxevfh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpwbwiy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlxjhqu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2phdrxeza.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hamfvglb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkavsbc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chautwzb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmvdgve.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuthffc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvvtdzu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ielgfkgl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqvhmag.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kffppiwt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwlipmx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnzccrp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqrmzed.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgsmsik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiriwuz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdtqqp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tohwbfqo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fouogrsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cliholge.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tepdlome.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hikmqrhi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2plrymmnn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gruszkbv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzryhyy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiogmql.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwdoqiz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vazvnnhe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2umotdodm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wllooroc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfglfmrl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftywtoqc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzloiudu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtauvla.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdvkbae.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oanqohom.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcdgkjy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoggspr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwsiert.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyryfgr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2glfkysbx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvralyo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmeblr.html


<!-- 参考信息 -->