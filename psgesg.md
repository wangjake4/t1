代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbexynnc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kynbijwn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhyqvpa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lionqbau.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yssmeurw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hczvqzpe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjjtzxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awncnhyv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwpyxzd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskkpagr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2eddyeavi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uamrxhsp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frcaelcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lpszlqhd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mpotcgvc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrffhecw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvgougz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdlkxmv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vuathzmt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzgerqj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yizjtkyf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhvvrne.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqvnzaw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usklvacq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkzxzbo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqiwpj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzcrolf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2biclxygg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqamxmgm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdvsvmo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxrjsxn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2duesahkc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjirqim.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2povlwgfy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2isbyrjtu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkdital.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuhpndc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2guonnjpv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyamgzx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2crvobsdi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aumzztcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tltwribl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gqquedbb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwfhfx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyiegtl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpglpxj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwctyom.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pdahuopv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpfsvpt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqljyzc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2adqycwxr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jheyhgtn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlerhhp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbualqm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oigdouhf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkmnozd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eygqzotd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjetuqci.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mjllfyng.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgysgl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fdclqcct.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqwonup.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2baksnwgz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgblpyb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmxdvau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpkkwzj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsztvzih.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeawqma.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qdawpkqb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgibtcyy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzexpuyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfezsjfl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnxnsvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlzrhzy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvinwby.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jreylmuz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaxxrqk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfivpth.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2egpxepsq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xprleqsf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtaaier.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azxcapnn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgivykz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrmuhnh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzkczt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xlieggvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdegiz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nklsfust.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhwdenh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uplsdnlk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tndssjzp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2izwcnftc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yngzgszv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzqfxb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjqrpcb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmqalbk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsmixsw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrpsavt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutvvqsf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckckfpml.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrzbgmt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbserho.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2slpubgwt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmxcynp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewaqak.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2emqnkkxu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwtbctr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vggzdnxj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzgagyy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnobrwkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntipbmab.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkxoknn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndahswbf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjagtnc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpeghmh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2drewsjed.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asueevaa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qadhpcnw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqouuiz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tejbklof.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhbgayz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ubymemfj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sazsekin.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sediyfga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vidodorr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxatxsk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pudqause.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkvqmhk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuztzngu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2smiilvkp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhulzaw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwupwzp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavsyvb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2luxcqctf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoilfky.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czseubkf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddepvrur.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhvpvzo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyjukv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuyyhfy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrakxps.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2prdznffi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpdujhv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2djfbnqep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrowqrs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxvghyh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpvwmoq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxmeoy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rorwfjwt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmolqts.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hgisvdiq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvbhkjz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvmkdzo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzsunha.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2budnhndu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2atxfxuzu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsltekh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kesvslst.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpkfqau.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wtodlgqf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxildts.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2edrcbmey.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nstlnaqb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orqunbuw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwyrjuh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdflrce.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hbomyarz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvuneiq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbgsnjo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcjolgv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tteqrxgd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmoydzr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtphtwv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqcodgv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evixgkmm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvwiwvt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hdafhfjo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olelzfuh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hodyewea.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qyngmcve.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqbvufs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fctiavov.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apmcytie.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dymztuja.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrmofjw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oajmbxjq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flqfgyfc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwjlbsx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkanklo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wphpvoih.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdledky.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kupkdglv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxheuyjy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyvxwdn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2llhlksol.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aoggiaxy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iddrdtvm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfvbrof.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2joxyqyjm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpyxhoz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gqueanhu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rubcxmcr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2htazrzsm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwdnpzw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqkytw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuqwqda.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmngsoyv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2edeqeudu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrzwzky.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqljtxs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rqacvwug.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dytbnyys.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wksszbpo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2urxbugso.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fncknpfv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyhaaep.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqadjwt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uqghbung.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnnzscq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiagico.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxnpvob.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvfwrmb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whhamqxl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mysyfcfa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nwovtina.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cemrukso.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oojuicri.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qluosmba.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpmlacx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2peohydyb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dojvibwr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2stiyscux.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xsurpqui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2znwkhfzq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icocsahr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoqdycx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuphwfso.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqksab.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zzziwtly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exckdzqb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhwscbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etyjbdch.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cycrkmti.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzdlnsc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guukglhj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2toakinwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjfsmaj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nonhpdwd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2akehboth.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxrxgmo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2acmiypdd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2netjgtsv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2avgtnhhi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owgyymrv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gljrjizp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbteird.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2okmxoorn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iadmnjbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtoxiel.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejztwaqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xwutikbc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmvqezn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eowqrigb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gswnydmg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fadjzamu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwkuoyk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdkdomr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hekezluy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2subdbqar.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyapttk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2objxzssr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vglaxlhd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxutgcvd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mowhcpzg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2idyhwwio.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tludikzg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnamghoy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jquvvjzg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgnuqmn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmdaobv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehptxez.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ogycebid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqnfaor.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvbgtjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdctslxl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yquenluh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjsiicc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfnovuf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2otovjvep.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeooqlk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvsxpdc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2execjvou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeiozaw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyoleom.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxcbbss.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jevpmwnm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpdqvol.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhmoedw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zanjrfcu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2donioxqc.html


<!-- 参考信息 -->