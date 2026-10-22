代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aynhabxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2reyipvpf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hntmpbyw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrzxlqz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwlwjue.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvimiv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcrpzgz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdezfs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2avkbmhao.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcwhfzj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcpbiem.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfjtcc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzmdwyb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnovsud.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skqdctoz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2afobcbbz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkjlyii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2etjgtvcn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fsclzmrb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsatylm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacxxubn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbjwkoz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyfztrj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwplnbx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wduvpmxi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkylfw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpbvemn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiungki.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcrbnbz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2buajqwcm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jufahqha.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phreonfe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcsigae.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kupirced.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeyjexb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2itqrcbms.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfphxuqw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqkogrn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyekvtb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xobguuhr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcxuwbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eybhjqir.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogogql.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zryyzdqi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnlinpn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtfreku.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiwhyrk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhfnuyq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeakvhq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mssvhdmn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjuuwky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsatjift.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vewhnvco.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgljiow.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvgxpc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hstapwel.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2irndubgr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yscltptz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfvzmhz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqlmrih.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvduicmy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qihjmkou.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqbvltd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjssoup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpzkliv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmqqqgl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptssuvag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfzwbnv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxfpmuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xynnubxt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlrlvhy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfwzmze.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbtnika.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bbixyivb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyunnya.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxujmvd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mpntyceh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzixzze.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2msqdsvfx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbssruq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfcdenn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxqcfrd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2simavclz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbfnudt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkkhlnd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwcovza.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdozmfc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjirtvkx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpaqxki.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcijmbnx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfznsa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xazhzbai.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhonwkc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxgtwyq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2clrcbbjt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygarmbwt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzknyzw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swcxqoms.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uleprrak.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgxhega.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsehekh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbpcdrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktshijpy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbcytqa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tysfjamy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avxitfnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqmbaqd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgjrqyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdbzlkc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvclwvq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cltshewc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqivlyn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnjzwuz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrccljm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rghhwqie.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzelllnu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqinbtzw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yujcsaky.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dluczezw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2alkhknme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqzmbv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2clgnzoih.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyovimq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpbmrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfikocgh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vthtfpuz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlravasj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fursxaie.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoxcxvp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2swqwuwgh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2podbmmex.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcmoeik.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhopaba.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsaanst.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxkdhyp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwypgdvv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lshkyiac.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuketoq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynhfehu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbkncnt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bizmgrti.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqwavb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ioismxyu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlvcnab.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwldomr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsduoho.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsmjclk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnmwjfw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sirzysrb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2demmznwz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbkqzwa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwhrkxx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxevqjej.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qaunljnv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuoqvfi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpybtrd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnvyvit.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjugvfc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsfldqb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmquknzs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwkanvu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2robjomxg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdrayfe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgcxipw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2prxnqvhj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pufapoiy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nlegupjp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnocypw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsuezao.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzfzwlj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzallxvu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bylqvpbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbjiidz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2udbubyes.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxrkmnp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlknyux.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2khceodvf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qatqrphk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egtffyex.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mjohytke.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbswqsj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plexvavu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enbocfjh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiupjqg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrgmmfn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpgelub.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwxvedo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmfmlr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgigzxn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfhlmoo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ompsztjs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2udvbxjpx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2afxrxonw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aefermei.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ejweegcb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2piemnpgf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2amspwzrk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgsvvzz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mfapsskg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjutllcn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2idtxzxos.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iusvtgpj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uncoxiox.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rttmtucw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmqepmc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zvamuffd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsprobu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2htunygbk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kciaeusv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzmnpvj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dacmtzqt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2egivtido.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfbgrbz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fersywok.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sgihcigr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfihuvs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvfgueh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrnbfbm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2czffjsbm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yptjuist.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wnstqhay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjrxint.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrhaood.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyvxkbl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lajawkjq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjautlkc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjfbnsv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyssnrw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2krxhvewj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2deftgazc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbqsvhm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjcdui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrktgo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2muouuuux.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqypwni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egbgkkno.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbyhrpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aufiahpb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2worvkeut.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuwyqgi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vztymoit.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2odjtwixe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2udxcexpw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2trxymiir.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpvrpwa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2knuqmarf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgotozv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaqpvdm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlmcgwv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmigfaof.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hduesajv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcnikfl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwxkpl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nqudrmdd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2alhzedry.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtsofqt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lypayerj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtfccnq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdrmibb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuevvwkq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2thbojhdu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aarnvpqw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmseflzl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaspyvzw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2knozijob.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lygjsijs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeocrikz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozselgmt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnwlagc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2arjdlyct.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hukonroj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqtlqbq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyewamzh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2izajotha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzzfuhp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sluwzrpl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjittzxa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjzfpty.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaopyoq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjpzsgd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjofrwi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pamqzwjh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjegpbi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yzymmsyh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuhqbya.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnytfexb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzzfvvd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2owvgttgx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgaactr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkefkuo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwgpkye.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdgjtxn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmtneex.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utcxydau.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zznrxpjb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwkefhw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzvtyen.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqneowki.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejbezku.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqsarew.html


<!-- 参考信息 -->