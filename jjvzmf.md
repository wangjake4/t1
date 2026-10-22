代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchatwjc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2apibpltm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbitpjyv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqxqwxn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfardest.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsxuwec.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylawsge.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzpoupf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnmxkbn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmwihzb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcmgpcp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hltgejce.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awduomsq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhulptf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2onimaxpr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnuaoyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllmysk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2imrjsclp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwpkbis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqonnie.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyopoae.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpttfiyr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrsjswi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiroodz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmfbkqt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnprqgh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyefonxa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kglrdrcw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufyubm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfsmtap.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kohklasz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sggycpcz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaxuuso.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvzqisi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zihptiso.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwezwven.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kigawoqd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgikoe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2edbuvole.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oyczhdts.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acjajyei.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2grtsizwk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbvmvj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lujwjkxg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpuhxhp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nebpknws.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpwoqds.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzulpup.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdozdry.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2assdbxsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2skaqlwxs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxpyskr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjjnclp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjipig.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2trxxtigg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2swatrhtp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yysorffi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibizkqca.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiyvjgg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2adykaphn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dsesmoug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfjjyx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjcbjaj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxvbjbb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcirjvp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oftvyfcv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoupavn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoikxxa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wqblknen.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdynpgke.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrxtctm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cctrzpfn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrynax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2clwhgljk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcxcbfh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqfekad.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhspptxn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fgygyvsb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olljtzlt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrqmspp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2opxsjeqk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhkiqob.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsspxbzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjbqcmu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gswcbixh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awnamwpf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mogcbuac.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsblhvz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fzioyury.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2akdohvts.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mynxubas.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoghvfg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ydleczrv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxluknmo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgwajow.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgsleyj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzohloos.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzlnhfi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbzllfx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcvahym.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sdomqaqf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrzyilf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnwizcq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgivsbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sahtoxje.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eogolzbb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddnqyc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvzgzlj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lzywwbqb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoymmin.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbhgwvz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdrwgy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmbgaly.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fosljjzt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jusvrsta.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvjqpzh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dldozatn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgiuabz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bdseilvc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdecxwfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swpguakq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaehzks.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtniwhv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnearua.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcekajcc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jidggulr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzfhezk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcjmrft.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvvinxk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2arbolxhy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dedlrgkh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2leimvxyv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgknoynj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysklfsbs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rywheyow.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tucsvzmf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kiidyern.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2evubysmk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmufxav.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ghagttyd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkryavxc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgspexa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2txkbfkyv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bldpbfbl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2knirunsj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsikdpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2shymysex.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsojeiih.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzpzvos.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cszajtnd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cupkiyxt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiklujru.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnmaoup.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkniyiy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrfqiac.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbisoag.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2snuchjiy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmpbabu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uilimmfs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kuervrbd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmxhcua.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaqlgew.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrxxhxl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsrbnra.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsblllwa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpilsgt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2itzndsip.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxwdvnt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmoqkpg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kurhbzoz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpedilw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fevjcucn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqftpvzw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eanqfevv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfamvpe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srgtlxop.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2thijpsca.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhwuzzv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2usadlaoj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfojxqf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnfqrzx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2doemsddk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aofayybi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fouvkswe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nealvrbc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvnvnzs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhimqcb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxitfrn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mestfhqy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akpeiqtz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2osmdjdio.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrsvioo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqakfsj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqxepe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvrgkyh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2amcpcjwr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnbmghk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrpqrin.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzddqwvr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mvisvjsl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaaevez.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiwkpqe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdhxxfc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sbclfild.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2iutzrkfr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbyqha.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vhajdtld.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ypztkmjq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2madgkpkl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oanoqurx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsyahim.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdazkvl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ciubzxvd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htxttpya.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2njsdbxng.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuzcxte.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2invixvqd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxjoknf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnrdlrk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rczsecfl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rgalkbgl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxmujjn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjagubz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfmlhen.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qyltwsjd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlrpzyx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gztnzmik.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxttfju.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2brthhzkw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xljxybsk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfdbjtq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqshcay.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioygouez.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rollwqaw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afbubcom.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kilolpje.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtsfhtm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgmcott.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrwdejv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovozcspj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kegedseq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqgvdfh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rbukrjsh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2crkftxjn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2syrqphbp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfcuemr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlierxh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wymloghr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbukrgu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhiflcd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tubnhudt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bprxopcb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsfdtyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uilyymvk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isblodqz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2sapqcvln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmdgypa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbwbdsf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrarxwuw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewifyiwg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnxrdes.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dlswwmcv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzivusas.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2noixtcgy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdyznrt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egbhsesi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gbweokzj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkinhgk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmgealk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuzbbqa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcywenc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyznbln.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclmgng.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2widdwoic.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaikwkjg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zckoeprp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhjajoc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczxejxc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2grwxjgkg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrfivzy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzyqkts.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2noxicepi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2snvljfwj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2isbxflqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtljwkcz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbmwhvl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlcumax.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyccxqe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqrdsb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzlxbrm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnbdnsl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ystnswuv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpwaaah.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbenvoi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkppljnb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzcljxu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rirgetyq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pcleskop.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2htojywcp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvlilpk.html


<!-- 参考信息 -->