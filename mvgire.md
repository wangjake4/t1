代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zotjpvtx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdjrmhv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rywhqxof.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2psygwxxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2loxetgba.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olshdzpl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnlhiim.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bodyzbvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoybdrir.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2edehfuya.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkyhaut.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvrdfp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2icnlogou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atbxcavo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkyutnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkmorcr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsgqmzn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wufiimat.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxyooeo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcniokvp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxesppnx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxvoydo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2weebvebt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfrzcme.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gqotfchr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikekyhfp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gddtzcnx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcshyio.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkgekiu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2watofcoe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2odfdesfz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjouaux.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxonwp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgfukuo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2omthbfoe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgctbkc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okxpvbrn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vctsjagd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcakucx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hthidfdp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rttiibmm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wupozesp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzbbqin.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2diahrbdt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvnalus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iridaxlw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uatyjpqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnovobbd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhkoumr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vusrbgdn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvapevos.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlonlnd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvzjjv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpnxgpt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnilblk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbeonbk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2foottzef.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmflkpj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2snbkvbjy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfucxay.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qxertgwi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxkbktq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ylieeywt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfxudzn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeqghsl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgsewup.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmfwtjs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqfxebu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kactrbze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2evqyoebz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtsbuqx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mktzxrhe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmjaqmp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2oilagoai.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2olphkisq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwndvej.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2akbgjbwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsynbhyc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jmldnegi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgezwig.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkeddhb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdkqekl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2enwfiosc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhupiehb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vupkjnhe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwjxnka.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhmavdn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccetwrjg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtjvbqk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwytfpp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uswvpwhf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhmmrnd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjvetsb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeacgij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cauuisva.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdgxcyz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhcwohk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zivklcmr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dktxzgxa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpaxxuk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmjrooh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyqndnf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbgtyty.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmaukwf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zxheavlx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrouezyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgpaeiq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrmcjya.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpobrxo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrcojfy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ravywggh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elueygpi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wazykqqx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yipxygfs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wypwpzga.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2teaqlzms.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbgetky.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnmgwiy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idgwbkur.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiozcjd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpresaq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjimcma.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkfpbcc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yigeexjk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyusas.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2djehrbvg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvqjzly.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmaxpjf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyilxxh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrielaca.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdlcwpr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvgmejf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgerncym.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnebdlec.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnqyndg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xtziidhs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyfmofy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfwwtzm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jceezpww.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyjftks.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtjmxkz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2shgtnfwd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjkbwzn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nemtbest.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgykkava.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcqkspb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxizfoma.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dedphmqg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnequa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmdoafc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzmnjij.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2abtzkxqu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxsoozm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qamltjle.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xutlereh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoargxci.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrgyybd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotfbbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlypzmw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgmwkwb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2exppxkhb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mxegfanb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lydxyrss.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tamsyiwr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqutdfvh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcvuygx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chhlwnze.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfhyvip.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sovxnlxx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cfecfnpc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fgflapkf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgycmf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoloksq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iksndczs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mqivrhib.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbjcggn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylflfadu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2etqnkxyt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwngzwb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyolmgnp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqgvmoe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cavemoec.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcewpffg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hefuywpp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqynkrq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2terjusct.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgnzryy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sguenuwl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdorhex.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpjbtor.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvmwpau.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiqgfrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzwqpic.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gbphttmh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2flzkmyrt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdjizi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtutpi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnoudx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2reuespzm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaxsxwm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ailozdqa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fblmumjo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhsfxlt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rubpxwyv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hilcfaal.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgawluqo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wfklxndr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ewerckzn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdpuxhg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbfaxlt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuxdnzu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2goniniyg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgcipbs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkilktn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uifchrrh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcogxrqz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuktuhx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2smryehpl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvskjav.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aixjxdwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmkhxxl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rranwwek.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwbiwsg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbrjgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2judewgwi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpebovo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxhpags.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cttbppqv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2siqwhzuo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mltpypbp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtzzvtg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2miniheqp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpzxgnq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouegjqzm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2liyjjdnl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvqwli.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2axfbzzbm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbxupao.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrblyxj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rarazzbz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yewgztna.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ztifsdaz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2geuwcdkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdyshps.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwfekeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuwcfjc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tewhlnbe.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lxehoffu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwolsox.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwdhffe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vawegsnh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoevttwy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnzcwhz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ontointt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfqcalv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfackbc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeyvfzj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acwtprjb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkxxbgc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnnkbow.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcibblya.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2udxjcffb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjskeiih.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxnqdsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqntjn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsupkql.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxsubbj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxcupny.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnienl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbpmwzw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsffzdm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edfijrjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hescgbbk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgjixnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2smcoebvg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjacckf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqgtifm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpadoxw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlxbwbq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmieuo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dalcuxnd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdboumee.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2chquymgl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isjwafhf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfinncpw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2erjgspmc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyikxpc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lktmklxc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimipkr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2msmgktyi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdccald.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qcesjkjj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2owwpywlz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mumsqmyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvredquq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zeomltwq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nupgxeel.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ejywvfew.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzclogrq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqdpzdp.html


<!-- 参考信息 -->