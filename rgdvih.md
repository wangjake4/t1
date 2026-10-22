代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyoqcee.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpskjyr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgncomra.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdmacey.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowzeull.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddszwfxj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svrljvay.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vavcrnoh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwargvc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dadfvzuu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvfyioz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnffxlr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2imxokfnr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtzxjs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmqxzpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkxfhsc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2igapoacp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xmimcmra.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywofczlk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzujvkzz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjbfggz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqcyrna.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iasqbrqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkprexe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzslglw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sapoimnz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2peqsxbzq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlqtolh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emaubljn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rkahvegz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzkqhrr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xojuxure.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgalkklh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbpocti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiiwrnm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwfnfdt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvqpkyr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxisila.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wioheesx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzuokdb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnkqhfp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2liyimfxe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lakvrydv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yutvggms.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2afiicotr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwwsqcl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uzykqals.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkfxlw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzffps.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2adxtklqo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvzoqnw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pjakmxxa.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtptiek.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbthtngk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2arerwqqh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzfbdgp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfujwuq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlqsjkw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aolofkgd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnihqbzk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vhluexan.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yahlduxq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgkhmam.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzklldh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmxomrr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwchhue.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqbipfb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2olccmcqo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhvkboo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sigahomd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxoprdb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ydomnjro.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2etlminip.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2irjdxsgj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2menjndrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoddinp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2enqjlsvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apxjeyut.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyjmlxd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bcekdaot.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxtzpil.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgguyam.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfazthlf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plmrqffj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdmrkzb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kayiwubx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2treedswd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcyhvb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxdauaw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxflrud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkduslwp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxajnxeb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiqeetk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxqueoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyewkjj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pyagcxxl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2avqtjgop.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfxxneo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzvpuju.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cyskvajz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkhoixr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpyzysa.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2atzjwixh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnzhhpn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zlusaqfn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzfwcam.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzeauet.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2foutkzlp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2crhnbgfc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfxghcq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2caarslia.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2accoovyd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oeidjpyq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sygnrrlp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzsvfoq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2naknkzlu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mevrrxzy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdvyhaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpulsxft.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxckyre.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2giinjgjp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuicdoud.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqsgzom.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtuoiyl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfcpybl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2phmiwjxk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxnraqu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysygrtdb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yajbatkg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2floapeyg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaencbu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrsspkc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zukkezfi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lpufypuq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgahmgxy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhbvmqf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdundsdp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzugqwb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvuvlhf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtgtbov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eegrlkow.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbomuln.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpbhkdg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2annzxhxl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthffied.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oxthkwac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdakese.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfkqdbb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqxeloe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2thugdyzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ingdkhxs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kcutxrjv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2islpmojh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgiymwx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2szycogla.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfbtxof.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inxuohiy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhdwfnd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcjbkrn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lvujrgrr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eltwompm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gldqpfek.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dunxjpxu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gngdibls.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fuavtabi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfikivw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkelterf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmjlvyt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jltscglj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdlivjf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2spwfwgps.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cgevtazz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwwnzsn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dadiwfos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzmbnl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwvzrtt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuefxnrl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xljmgblw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiyregv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtntbrrv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwrkqjs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rggacznn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfnuqby.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2egrcqsdr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hokefoco.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nromwphk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuzqfpt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsrfrmx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfoluur.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dboparoq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drbszynd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrepwpj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjyimcq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrlwplp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoyqiks.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjmamu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2engwjpzt.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmlevk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2quauznom.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sycophog.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2koggojgd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdnpwqu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gugpthhj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhtxqse.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2puaqgdxy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqlnjch.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqeztin.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpabnulp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fpblbjmu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdkxsjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gefvqeni.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fheyukvy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2esdhmmcs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrcizn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfdsyom.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2elzbebmi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrlwbrj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyzmpkq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bxonwbho.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvtctzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpobxxpb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uoltndca.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjyswbp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnuvolk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzelkhw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhebhxc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jubhgwky.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ognowscf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2shfyydbb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyrdvnx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifspodwi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wicsqmwe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2joseutag.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiyjumg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2reyledcl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vwazuhlj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2onovibow.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cloehcqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oflkdnxs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkwqfha.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqfleih.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqdymfo.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvlrleb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxadpb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tdanekxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azhvcxpl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcuziyb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwlxrel.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oecbncwp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2setitmpb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxqvgye.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrkivoa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiavvls.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpcaexr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jclgwiey.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsaruod.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qroevklj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ildyossi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2azrjciqk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dghbxohd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2slfxuays.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzyzqmd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbzansx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxmfcks.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrsnwaj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fidevkky.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyiuite.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdohmabj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoajslbj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwsymzb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrulemg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgdcpgl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tigpbyxn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcsuytl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvvlbwr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehstkiol.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dciyuogs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfzqywf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2okfzjvmv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2egnjgsvm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrsnbzh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvlkfiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyowdjpl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmvnol.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2orwxhmrn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jlybyses.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdesodc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqmxnyw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hszrestc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxepuqk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sriexrno.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2phlntakk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmrwtse.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kggqhvpe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uioazsqz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zolpuqxf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijygoray.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgogzowy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhxxyyq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzpbyoz.html


<!-- 参考信息 -->