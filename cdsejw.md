代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcppwjx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ktunuxap.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujtjuud.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfihbgl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhhqslb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eegbbows.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bydfpezv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyafqvmk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eplirald.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnijmzg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ttehbkpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2svietvaj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfextwu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iamccvnr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxofgd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyannnz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2notxmsyo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhesqao.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abffgvbq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmcqcwf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wohfwydj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tluffxhd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2poumckmo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdsixjl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlskbsk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdryyff.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zkygvqdt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2urrpoeik.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfzmlfo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvibyd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jykkztfz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnnfqhg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqkswni.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fytcyjzj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vprfvkko.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhqgbfs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oasusxwn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdftputi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgbmvkl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtoghcm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrjatpd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbvwta.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrelunn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfyyvfp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2plblspys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvkmyar.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvslhlo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fblkqmjf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlboelg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dviwanxm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcymlkjv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jklodgub.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2etmyounz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcurwypn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2piiamyab.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbxrzqi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzlycvc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slwxacks.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2eytoqjpc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhbndqr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaamsaz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wobuqizf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypurhprg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2txbxkfdn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2crmzcvfi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbparxiv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gesucfwc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaermny.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lcizvuzu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gynqxerj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouawlczf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrzhnan.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2njzqahbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdwjxjc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbxrhxv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrkmvbi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uuitjcwv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocixcszp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcmcwfn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuuguiu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwyubof.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agfahdxr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2htdgslbs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrvcbss.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atthuwtt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pywytpfb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjwdqrq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fithksny.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iqumjmrn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2szycfkec.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtinsbs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2caaecbgo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaligrn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uncteyip.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iaednjja.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtxpupv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqqnrwv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pprumiri.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfufzxvi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbahwsl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvhuzub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agxpikzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyefvpi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcbbcbt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswiyfz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxkuipb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tonxinok.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnwphlp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacjecx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2octjzebd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cikcsqih.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmmuldk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmyumvi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vihbrwsq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfestje.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqkhjhn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztizayyv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2daednvfs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqbutjv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtcrnqi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsgkddb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlssydlz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlxulsa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lchwxthx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2owluxbxw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdbapho.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaagesqi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgmwrnk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpygevh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxjihjg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzdcbdo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2evlywzrf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uimpygdo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzrobce.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfppdon.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdgwltd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhlzxgm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuwzfox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eibryfou.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmrqhsc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsdpght.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyqzshb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grlkmkhf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zcppvcqs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iookkmhs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcgebwz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvyogu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoysfzr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ourzloxb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vscbvaqe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnfvppc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatxhiz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkmmkra.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrxxjl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmumhxky.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjjdhvb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2anovoked.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krknyaow.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2meujwtfr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qnadmwyi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpfmjom.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2stxaercu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leeiqdui.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgndcafw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdjpolb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpdxrob.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqavuwh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2edpemaaz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcgexse.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndlfas.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2taaooupj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfnwwry.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szrwsiwg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2maumyide.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pycsawvj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxndirl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyuzjqb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tntypclf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyepvs.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpwgqet.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgxwcsc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukywanee.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgyukw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2efcgmnll.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqlvirq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdmbkzl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnojjbup.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfhowpa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqintwl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpcghim.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzicqsg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2edfododp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vzomacbc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lofmjwee.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2leuyverg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuhsejm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnawyvq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfpikyb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xtahlylg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mudnfqdg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2phqbleny.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnjyqjt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmtiwgb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uuegvgjl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ilktzewd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwhvkbo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjpyinq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrztyic.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fxromamo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaxagnw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfbqyaz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyrueqt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2damlevwr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfxdncd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhimfipz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jchpelaq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yimfzzaw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpdmjmv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwsphol.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmubpsko.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqpleao.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqgzcxy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqabneil.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqxpuv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jlphxvkh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gerdgnth.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krieoces.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uydifizc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eogaakzd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afgushke.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bofbmhzr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlwhgfa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2grjhblgg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zubahbvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrspkulf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2favczewx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvazuqp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzsjskp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfyfpyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhquxknn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaivuws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuaedtc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlvytuk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprfvse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbyipnl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fapxaefn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bylasxgi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznvrtu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjjgdlf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dhofedyg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sziilecy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoeukvi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brgrbfac.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeacnpt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxztmpj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2alrnvacz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tujpsqae.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulytjkfv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbrewzx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjwjco.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2himkwbmb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeuakjo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2elggujva.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unzimbyi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2chqujjaw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefpppr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqxenyg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vitfeize.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjsunqv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2shhnoobb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjwnjtu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxtbunb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2abntvbqy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2udnsfrdm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrxuftj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcurssm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uccnswnn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arlkqjtd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfontbbj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcgnlwu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqmhka.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caxxuvcw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kevcovuc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpurmii.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qokbneye.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmpeaqt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeviqosi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrqfihn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgggdnrv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgqruoa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2loqqpgkw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cnilqskr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpystezl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2izdmdnbx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2azktfjvp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjlcchk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhfywpx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvdqrri.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydqymk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnegkzi.html


<!-- 参考信息 -->