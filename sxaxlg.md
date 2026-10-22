代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvgcltt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllvffyz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ifybcask.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cihgdevb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxnsmfe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2erinkktp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlffdn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oklokwlz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtliaywt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqenkrwa.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgnfxij.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxjwxtc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcatdq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdvqjp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xtabjwub.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyanmbdu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhkjyhp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2unzxzvdl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckooevmp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eldvsuds.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfcxdep.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2utzpkrof.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cniwpvtw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiaoysc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eunkorop.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2upchbqco.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bewlskuz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xazxhuqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpwjctv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bknqeags.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvywevf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfbwnpd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvqlwhb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2csocnjxt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgkeitz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwjmfct.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qooyfxkl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiptqoj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hccdrbut.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhtgklq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iubmpswq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefqjari.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtvyyp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcvasss.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sujrxvuk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sggwpeme.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ossejfjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2weanxovt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oakfcmrq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxzlhsb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uwamgfrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2upptkndu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgtaarp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyjqmlr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2knisstbp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2evvfygss.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdahkrj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqugdmm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uminxuqd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhlmui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbfhofi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxskghlm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkutendi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chypcmve.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkevugzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlhswcw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyqjwuf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjchaeq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ovffhywj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ndstkpdk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybemflok.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlecqtmz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gurjqmym.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqexbcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vevrdegv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wycfpsoo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izcnzexu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ombalcxf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoitdgi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pupnquky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvmcerp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhaalyc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdimuhq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kycrrbsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hubbzjfi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtzwppg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwawciq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyarqbo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxurkfb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2riggpstz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvmvvvj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmfkoh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2flsqmnpn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjaoaa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymxbii.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xucdfdnw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiqtfkw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hperqpxo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jeflloze.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uarqeomc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nokqbwyr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhmtpfz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isuoujvm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyutsndv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjzqvvx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsfjfch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlihvghc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwvegbl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqqoalf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfleilsq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaxcxqt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbazfwtj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmawzmfz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhamphv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vphvzvoq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlrjzqw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjysbny.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eltdhplr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkbclct.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ucncodui.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrrtcfk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhdatuc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2crjnpodr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmoalix.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzuhdrp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhtjlcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mushusbp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgekqigr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmtpfen.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzothpd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qapojoqj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwritsf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqahnvc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kqubpvhk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkthvhc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmgigjo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvnxhfg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkygdcje.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmlbkik.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxhwuaq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcccrqdu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftasjpqn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcsnbex.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umjkwkue.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eghfsmhq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkgdhdq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lwanuyue.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2urrqzolp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qsntjumx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrvnibw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbxxkzt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2efvgzjrx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tahibtrq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnagzzo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctptozrm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erwmpjvm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfoosgu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2keavqgbo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sixtyjml.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hljbecez.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhthir.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmqbnhl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqikchb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2douhvpsa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oynukwwz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbgcspd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdvbtjt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2koyfaknq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqfnbin.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ausmnagi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odmeqkzk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqnyurz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpfdenw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jthcjbno.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qygugkzj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmwoyso.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuscrmy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwmbtbm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2laivzdpq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bwekcpdw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjwzdiu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnvmfcq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vmolgdva.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ycosjunp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrnosnv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doszkngo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uavvlfbu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuuunxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2diushplb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xclomcqy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sborqgwa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjwmmxj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ldliuzem.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmjajpx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvglmzp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jwooqews.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlaycdw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmctlpdc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxuvxzg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtulxpdw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2odividej.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pceyhuuw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhtoduq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaanuoc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lxklofqc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vstwwwpd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnvhdks.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrquide.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2goextqcw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfjeqrd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2alsnevwy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2blvouzxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2einiispg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gihrhhlc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdwvgnw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdngsri.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbqjuhv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbyrocm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdeldbn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stvcncet.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2thwdelru.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnovefb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzqotcc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbvpqqo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2udiaoald.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpfrare.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxpokpc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzhvaa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhfrlvk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbejfjo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfkajxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyrzyqg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nneskgro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsxgiff.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtbjuoz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhesomh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdhyggu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiaxuxn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynygeaje.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvbtepz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefhhdcj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rndbnzom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrwujif.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zluerhyo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdyfxd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeziocg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zimmlasp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrqlxvo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2srvdcjkg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmlgvh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrycuri.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdupnfhr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yobiebat.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvutzju.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkgcuge.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gseszdfx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjszszr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeeatzq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmygznqc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcthfvr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifkhqg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xorosysj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrraxobi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jimjkjzp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2srekigga.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjslmqkc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsrjasz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2raiwxpeu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnjqwrz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uduwjoqr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pluqmtli.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2laqzccrz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtofoldp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuvaulx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htljaxla.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2glbctbxb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhbfbrb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcowghp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vriyslun.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nodaugpo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotydiz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtzvysb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhynavtv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojbrzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2soimdkdd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kviuwbvx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwcwgqt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ybehdzmi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xutolneo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fojibabk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2veiegrzi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rasibxdd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxysbax.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwsige.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpggzhts.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2utullsvv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxfbrkg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjgemnx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqrmtay.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhsevvt.html


<!-- 参考信息 -->