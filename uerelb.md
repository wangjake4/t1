代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qidruptj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uegpsvjc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfsiuup.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhanfnp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjoquao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctjotzr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyycwdc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbhynvq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kcshdyty.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dftijsyh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zstumkxn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhohwlak.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjgnowa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2owzhcbes.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvkyank.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyugiik.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2veumljst.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfnmtvy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nboibtqp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2juttlijd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arftkvth.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjwqybl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvgfvlj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvyrtw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixzsmw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfqzizn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaoewsj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2whbyzlxa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpphare.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxnkkwx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uukulygz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhnbvud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wonadkqw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpngvd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2viatnwmx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhudjiy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzinvhw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvdfbuc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsdyaek.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rucxrvcn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyergme.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaimcds.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lutwprcq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ratxnbzt.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2edsmzmxn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwumnenx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izmmophc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublalybu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gowyqysh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoxpxik.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2boueehaq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihlccbg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhpniqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhpecuy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgianis.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjakfnam.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qohrypxv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqflpqr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvjjzed.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbebbzo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxggcgvb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcqlhjq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snmftafk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrnfzqz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaaoimv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sicxtsxo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnixgbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgpfxbx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhefytx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teytvlnp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuchpmqi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxznala.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2eixpoxzl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyisfeo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlvmrbo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgkoszh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2teszuagh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklixdc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dehapfgh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfxbdyz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqhozrv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpluvaa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsaaaon.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naxcynwz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwskgqo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhddvzb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qdluxvie.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvqqfdv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnivuh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoawjkx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeudqqh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xcytldeo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrxlcc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyjscbo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mllkdatd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkdxwcu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzlwdbb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmbvdpn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svoukthn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vfabohmo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrnsgx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tegiuhfh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hotinrqq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbuwtfp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jeimbwwo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnewqtiy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgfybsi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hybzlnxk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utfitkbf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyuzwyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnfnhdk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vafaymwb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxaeayg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2meytlpzg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjdnnqt.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzsaxgj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mafaquht.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfhqnbl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrljmws.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtqhria.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgvyola.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzgxzk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnrkcqw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pphrvegb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyfzxby.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqutcgar.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmzymhy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pifrzvwj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wouhteqs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wvebpnfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsbzxuu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfbqgpi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjqfhmr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bsllplfo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2btefqnnw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqfsdkm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoovuhvh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqjtbtn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivmkxz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xynqpakp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vqflvfmq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzuqcbg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2psznknwa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mlddmydr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kplpacjs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjvrzmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2awyvtepg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxxqubx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrzgapb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjbtvvq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrcogpt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhpyhbd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbshqsx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2duhixyag.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgcrxod.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhefgbt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzrsfvw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqckvnp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qggbcllf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mowlfgdi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpsyjzk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkqmetw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nphncjba.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqwrlmw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2muimhhij.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgwggsg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pghnsdlr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kuihcpwj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lohsshgn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjynoz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udinqltm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqlliya.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2otilrgqx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkiomoq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mklndsgg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2glcfcjmm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pajmesbq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgxhwe.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjxvuvd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2miykzdhh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gptqbyxm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rymsirac.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmjzyff.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmrxrox.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlcejes.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2czkppdnm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xibbaksy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsdhocq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoagjqp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znfxlfqd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2chbhzeus.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sojtssqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ptylvxwg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqgzesw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twneqdqt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2liaurcua.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2traqppou.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnecqtn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoqynwk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgmxwhc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vizxvpnq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2slqkcays.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqdpyfu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrpuccl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzvxdh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpheaxd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zatcpogg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnzpdfl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoylvbp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkvjvel.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqgtsyc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pszunvpw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qghyoovf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuzkutv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbxdrk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aodrkcmz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zekffkni.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwzskwc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiwhlrm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzldeye.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qfekrygv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vbovidbu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbohocvd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwmncki.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnineikk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2todveshu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sixomvsy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvctvjb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmyzubx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwekrqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxndrhp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2twwgmefh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdjpwen.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqcnqbe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfdllga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiytkrnt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2itlxixqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2depeyjid.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfyehjt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfajjaed.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvkpshf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsuesjg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2niorivvf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqzjwkc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydragzf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bplnrfem.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2abyqujjf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcjphto.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhtimmd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2linpelgr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjeragr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vuffuqrq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzwgdpi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzobkdy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsempbup.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iamsidwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jggdqlia.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eegfofld.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqornbta.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbavryou.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2idjgndnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgcvlze.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdhwjzy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmxkjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvvocdh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hatgxowt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlocmpy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjimjfnp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yppgbvsu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsuajvw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqtdowz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfowgbj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uidtmeim.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnoivcw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2clwavaas.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwexpqbb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucfxqwi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfsxyks.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkshaqkl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkaxrsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsvsqea.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pjviefvu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnhqrui.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxomkpt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrcwwi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oydpzwpd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeqlcna.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxltrip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrngdqlf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2owycrtpq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhfnmmw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dazemnjv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcloabyg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzchnaus.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjgqftl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mulqgqcl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qknejvjw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxodjqu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujooyszs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhpvioc.html


<!-- 参考信息 -->