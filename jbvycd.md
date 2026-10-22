代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbombun.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqxruzr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmieqjk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2andjzwfq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofohhzim.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnoqkxm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotqdcjv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zoczryaq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iblvlurw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2exugcucr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjyljpf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpqvgw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdzicao.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjundxwi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2syxwzgya.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsofatnn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gssxxqxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdyfqvi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rombvgxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfaymsl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dalfoitw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdxbuyt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2urzkeknk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqwadoj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwcxua.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsunsra.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2purlbixm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaeutho.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qirwysnk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnedwqy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iypqjyrk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsiirxu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tugtfqvv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zetqyuag.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcinrxzf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zajanftw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhvgoqo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlmoqje.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uqindumc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvkjsej.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpmxujv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2onnymysu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsbqfay.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2drjcvubj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgswfsf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prjvfcuc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpusieg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpgwfjk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2waqkpweu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocznznr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jqghklel.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2amckeeiv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxibsgh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvszafse.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyepxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqhkozp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwhcmnt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jystvfwq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bytyxsvt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmazrfx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyefxax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxckzcc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2auczgunr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsekksch.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvqbkzb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvshvcb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxseysm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dszcqkjp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yclaqzyo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xghxzlrf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iunlazjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jttxbawi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmeviys.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqglish.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfvibx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kidlkpor.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eavwdhxl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbzuegw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrrtttn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xypekzlj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtviesx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lswkxtsg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdbmckn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2imevmaky.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2miqqwncg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjltgqea.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnmnjqi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oulkdgkz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zitptnyj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hosshahj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwysntzj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eydwrasi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiulyzpd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aitgyifq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exzrbawl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqiiqnf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tipfioly.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2spkrjkon.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhgrghb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkgtdhq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2osdyakls.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2augdzdle.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dybsutrm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vowwcdij.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ccalzufx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfknjou.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqoetbm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrmymmi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lgllbfsd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqoghnz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gegncacp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uomwqssj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjazvlvb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmhuvmn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooknfixs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpexct.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhkgnys.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqofgjdw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrbbcxg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2imvxfkxn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grpdgyac.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2axfaeluw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqlwqtj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrypedu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsllbjn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsotccyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjucea.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inikbcxa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxequbh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqejgobi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xinubjhj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jixikbrx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvxsfzh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbptwvh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjqlng.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpzzivz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiclrvi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aunyacse.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2onzirare.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyhhhgq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fieclhza.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lglfglwc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeyonbf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vblszqhw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbfugnz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oipgwdbk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsmfnai.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2intdxdok.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqlwgzg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2blshjrcr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqdaktl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjfieqr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjknsdr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vurwmxuj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvnyri.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jieipjiu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtppifpw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aucavsko.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtnwurc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acqknidp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqeoqja.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kklagvkw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cwufjjbf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkzthg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvyovh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2anobixwz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2amajwcof.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2waudcwho.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbjepza.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxeulcv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwvxgul.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrjmous.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2daetepnx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2brfkhycm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2azubqous.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtliay.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vztqhttz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwewddk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrfsylg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pocstxnl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnuhgbi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmvgdug.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2roetrcos.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gobywche.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qqujnbnd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fedoiwkz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsigfbh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfopuwl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xjknqrvl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2apyqbxve.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaucdms.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiwvvmm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfhhomj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrapqfej.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaogokw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmnaobm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ddujgnrx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kygbbuom.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2arrtkliy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2raxvwsud.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjuojuo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqayoqnf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wlndmvgv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dotjwtcs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnfnxgp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkvycmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2myhowxox.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjljcyc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aidbpdmp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gujmwcfh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2echbspsm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oystetqh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2stfceruc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2amyimaeo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfndczai.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2shwzqllf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jeibuhxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrjtlct.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsbokmg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlstqbwp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxqxaey.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxwwpbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtbbdng.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tevqvjab.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2audsvdzk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fabuiotl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnxcaaq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bumensdx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oykleddt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xyapswrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2llegyoke.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2afobeadx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnrjmdm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtzolkv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tklcxrkz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gadsucqu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhppapz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqbpkay.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mviaoabo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gijgbkoc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iusvfuaz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzlpcdy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpsyzar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ahylvhif.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbftkvxr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2klspktlw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzebxft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnkzate.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qjporofl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khxabuib.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihafsyha.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmvatms.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tigueyqh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvkkfqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxaotp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2szzlkfku.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtreuov.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlmegrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkkzmlu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhldjir.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvwnosx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbtaprj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xesrdbyg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjcjzo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mvryajnb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjqwqa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrdptsn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpktdkh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xeepfvjh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyziqeq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gikadltx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2liiwagrv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaenkxx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqzhiso.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2upjdmncw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utyleabe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2svfwdyyz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hsphypqg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wicujnqe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvxejmf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eoicqvtn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrlufow.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxpvcrw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iphwssfd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2villfpyn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmehtxmi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgippxrj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sntypvkx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzwhszr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbnqlii.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htexpign.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xznwxnzr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmyvojx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dpstqzta.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmkozgm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ceephyid.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bymxwiao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cahnxnze.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjtimky.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufrnyc.html


<!-- 参考信息 -->