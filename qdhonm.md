代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfaapfe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccywulvg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dehxwhxj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnovfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iajvmisy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2khcqnaaf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hifcgdei.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2evaepkbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusbsskp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmekkfj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwinibgl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbuofqy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfdwvne.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsxabuq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvjdthr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqrawnu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vypqfizr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdhuhf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnvetlt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yabzewqd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsgpcog.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bpargvdw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqwtpdu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbocqfo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kseivsnk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pieegfcu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asdwnzdu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlviwnlu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fgemvinm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgswgcgu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyynknw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsxqlwx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sysnammh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zqysmpie.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2modrxoop.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbfwkib.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czldvefq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkvryxq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhgbaae.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nrewivwu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhdwoqa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qucdjfxw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsvmsum.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptabzifq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmrzrud.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2serypusj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpzivov.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pbemgzsn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmedizm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlqftso.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cswnuimy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lajjlvoe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhrqykf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2luxxnnac.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlpmhpl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcvwina.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjavaf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyheucgi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkwtowo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sczgfozd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbdxaic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urrorvvu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fclzximc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psadooft.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyncgei.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcuojf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjixvdt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwbksht.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2labathlm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmxhcqo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnpduxz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpohojmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmddvygn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yogsxbcl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkovxxru.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgzukxr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2haavlmal.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzahzln.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdxesvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vftwnsvg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdghsky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcjubmt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2orefmgoq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuqpbay.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuhtedr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvspjwvz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzqsgcj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmcnkum.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbdkfok.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbvqjec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyszivfj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bznnneoo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnnitey.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvtatb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2istcfpbu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzgptkj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2weplxhpi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mybfhnyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvvrdlh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zwihqgwu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2znbstwtm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2odyglsdx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jctbrlzo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkrvhha.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pprdezoc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddseillu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2agepekna.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2plxukufq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqdztza.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2joepigmr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqrkwks.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwpdnhz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wujlgcgk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaodibn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuxfkta.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blaoxddv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xskcewzj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rympccyw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kznbobcj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpribwct.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elzpxiuo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmllhzgq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhpsrdu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2clfpkuob.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auemzvhv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2crnkvyam.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omrdurml.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpvqjju.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bctnxhao.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2usyikdml.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzpnekn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndninmft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2upzibwse.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuprfzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzdnygx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2idcilkkb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvgygf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2caawqsgv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaxbetp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtojoep.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsnznyc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ehneeyqw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qaagnalf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilejnvzi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2clegpuni.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmldczy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsazshyf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njdombep.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvsblsf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmwvhmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kayxgzbs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2chvipzcy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lifkmwoq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mujdebjl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2shdooipa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqgbsla.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbsirpo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpnwpvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoevfim.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sylgqjzu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrvtdyh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wmswyzja.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqvkwpu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdavyur.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxsxkdm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqagva.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqletgy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxhsvpc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oftzmixk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uskumbzk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgyhwvu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2outpemtu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2thlnnejb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zosjmohm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpchukb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2moaqurmc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxtkegs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmlsuxq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzznjqwk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vykjmqsy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpaigag.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lphbmlmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzjuzsg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaumpuq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2czwketoy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgxswlw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuybypc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhtgjhy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsvaclu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaztrur.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgugwykh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwzaebx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhomnbg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otbicgaz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zellvsqa.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzfgnfh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuorgmy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiwevaz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfsayvk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwncxwi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ppviqxjp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnqcuta.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mfggtfeh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vrilhjce.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbjjepr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcdrotn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2egmlhgho.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smfuvcgp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkavbu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhzjbtx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsrszud.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yolnrkim.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpdogjp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfdlwns.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephpndew.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkevumx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqcmfu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rojxzeum.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjlxmmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlxeipi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaeyjoi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjqithl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lejueorz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dppixrnj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2azroewyo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tflxavon.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iabtyfms.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khoftevk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzqggyh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dyznydba.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yedczfkw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwstjoc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkgxojr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgztzun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyozmdl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rriagmjb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2aunwicna.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axvtvloy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvjyysl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2aakzgneh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbmmlyv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdhlzya.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxppkbad.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vllscekn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvyzoqb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nomlmopm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvmbrlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuoafyw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2phluqahu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmmejbv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vevixjgu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nevxnuok.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghjhaw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jieqftvu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2akcrefsd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqealxdo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tblcyahz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2clsxzsor.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeckxur.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yuglsdkj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eonwarln.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yrynbjat.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwzajuy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gwesczzd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmmswk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjrznmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuelkds.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifggyfjm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dagozbck.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwpmswy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2thrsfttl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fneulptw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqfwpiq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tocewgsb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwwtznv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmlpnds.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvsefac.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tklbpixi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2isdsgawx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2grboclpu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbqonox.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2spnyjabj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhqnvmx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqlfda.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prokisdd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkszyib.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoegkpk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzrbzjn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwedvii.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtiyqbk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrcbqor.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrfvuqa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjoktze.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2drztxnnk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcorlyro.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitdxug.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyktuext.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2miutfyxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaomuhr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2twcqkftb.html


<!-- 参考信息 -->