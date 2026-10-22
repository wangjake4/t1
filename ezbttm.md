代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaclbzkv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2almzhrdv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvatbjz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yeueiiey.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgjlvaw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oqapkley.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkbxwwj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2izkryrgr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yegnwciy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxsescm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnuunw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcitmpd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zqszzydx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epbyrndl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnexqqg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwfftnt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2deghtxtv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wptsqurz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzssnbzt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbluxrul.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2obgzecik.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvptwjdj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjepggwo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qameucdb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vunejmww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ittmksaa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoqwklx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxvrjtl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtvmvix.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qdembkzg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhcujnc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bqszyqml.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gowfhemr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwencvj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrwphqz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmtqlyi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnibitf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lynfitts.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgdfnww.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jplifwbb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2khtxwsjx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdnucoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnpmxjh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhbpiem.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcelalm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2drslqlun.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hudvwhrd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqftyya.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jwinlzte.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oshzlojh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsqasuv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ftauitva.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xtomnvri.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2folgmsiq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyglrcmh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvgzdgr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2edyykmpg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvuznml.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kghptupr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeeoptz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhhqzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zifnfggh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbqcszg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxrsucz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zlneshyu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2klmnghkn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtnujjn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrvcdqs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmduecxh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfidgpk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwcarmv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwjdvfu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwcodxv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxteawlr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzkclhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhvifxt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvceojr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lefamfui.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuvncun.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rjltgpzu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnypnjp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2onlqdiyk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpdyakb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjqfurc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2knoihrnt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrcjqwj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozntuu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeavqkdm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmpqlsq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvceycda.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvuqwms.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krpbydmb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2urtzeqws.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpgnjsj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yycmgqeu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iybuxpqe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bkowsvjt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iorbcdpo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2juzuzhvx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aokfotco.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2efodnooy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjejcwsj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2muylfdav.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlpnbpq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbmsldo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxobuz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2elgylkzm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjlkhzl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pojusdhp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2njgzwqve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgpifwf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rharmpod.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjibqm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ernfesun.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyzhvbo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjogqfuz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xthpovpx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqlpugh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dggnuakg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdxsizw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rztyefej.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkwokkj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiflqui.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuhfdbi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lihxexvk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2joezecra.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2davstusc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvbcqhh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpwqbzo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxgxlxv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atkkdzbh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zsenmszu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knyhtseg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xviaqytz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjbefud.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cplzpimy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhtghzi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkwifnv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxtxgmh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcthkwd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvghxwl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzofrjqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmrgoms.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgojdsv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnhxuey.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyvsxsr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2badhxljr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ydedbkzv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iunedopt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2toauzhkl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcjjnel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzrsrpd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2agpevwlf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbfbxth.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpptunz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fljmktnt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqimgsc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbhjrsr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2svnipier.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrfhynb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlxperz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rndhvlwo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ridqffun.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjlbnkw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkbgopq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vluedyrx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksplxrnb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarhqnk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ectstjbj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cugcivrc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xlexzpzh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvbhwd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoppegq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaopixf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2guzizdya.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srqjpzew.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrregga.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjqoqvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xitswwyq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tejxjgyc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vspenyky.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jizxklvg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoitfzc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2olvzaayy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtwbkdd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkchhdq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjnoodg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhqlkrr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gbplyspl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfwjiay.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dacqtwtr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vooxrdrf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fodxglif.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aoedqibm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvcomxs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cymsbqtq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2edppyuiv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwkdybn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2scmnhrin.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmzoqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnvupjb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cijyxupa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgcdztq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrbhgia.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aipkmove.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlegybw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfrzaft.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iawerrig.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2suxzabxd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gefwtsjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawccrtd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvvlfge.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqzhvtb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvaoodw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2drdltxxc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjvqehp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpxdccy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dibeafsi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbacwbvv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iojqrnwc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqayvnk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aktqngzr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bajwpgrz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuhjffg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uabhnokd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdhedga.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktobpfzb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fnorxxlx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iqizdvsy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lqppycvw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuqnqx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slumizjv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcspkzby.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkystgym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hceyqxqv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fodbcxwy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhbnmxk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pgscqeuw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tiongrux.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fywstimb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxuirbd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbbpsfp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jhygmpgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtcauop.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdsiwgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzelanuu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azmqdkiu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwhphwv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwnrooi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhwusug.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zximhkby.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wupthmqz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2emgnyqyd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ebltczpv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2otteakeh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzgmkcu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyyrfsl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amxoderp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnkfpai.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ftakolxx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bgymxfdc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2piczrrnn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlrzovq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2canekypz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nanslazh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2khivrgec.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udeyahyu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxazyne.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkocvdcp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobkahbf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2reyjarvi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjvtfju.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmkrgwe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiesxrd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tclhkfel.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmuguzg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbefhnmf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqdgtay.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlepdyo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjtzwx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kadamtxb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wapgvoda.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnogucn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zawiapiv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkqqboh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmsetmr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkzdnas.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lybbdhzn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nylwcams.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuabnvgu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmcjuq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtjtpdv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tprzayxc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hstrercp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwplsht.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2efmraagw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzbnxio.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kayqnqpo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpwreut.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aieyajwb.html


<!-- 参考信息 -->