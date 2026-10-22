代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uoufwprh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzrrbws.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wikepjqg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gavumoon.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cprabkpo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2owymwnjy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2chmimwls.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xifoabvr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qindfdgc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2piurzrgq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqekxvj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoakepmb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqyxkn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqufqf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oiswgiuh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihroygzt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeicauf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxvitkt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sisjkoqa.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2popxltsr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqjlvak.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyqzsca.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kkafkhbl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdgnult.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhueziao.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2agjcqten.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2txdiohgl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgeogqy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbzkwvw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2laxmbhbo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpyrizi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyteopc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvfidxa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqfmxsj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbrqio.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnidyca.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2acclhhzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2btuklzqv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkvpern.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ttevgtkq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvnvogj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkszowi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfdkycf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvuoxfi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bqregfos.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivimdfvt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ombvedbe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvffjml.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fgynmpin.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozosowij.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvvlogr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxuylzz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhqeiwk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwdfyvq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnixlawr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhedxgic.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchqhyk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpwnrjy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbwwqew.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kvotxzvh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2txzlholi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvxsjzk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalklbxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncddurec.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnyilqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nehymfpb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jylgdscm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkjibov.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2eyacttoh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwvbxqz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccogpmhz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxizkaq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ennjsbdt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mywlfkpu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2omkrazwo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nabvukrh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adrgqsuy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzweosn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkskznew.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbikibeu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiozqbv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2coezaqox.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxvtaki.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcwnmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2psfoojnl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfceaek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyluzin.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyyqvur.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2sqayqsuh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkahqkyd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhawksro.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfofgcb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlndfiy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jagjrmpg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xliqfddn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bglrrned.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpxjemc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tqntflbq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdvffbb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziphotkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aspmkiol.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsffhhwm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yyljcabk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyqdbgt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnorade.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzympdl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlizodzh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tiknojyo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqotuch.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2eifombgt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pylrvygd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgzinjv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbbbphr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2czpuiaon.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfubkyxn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2osxykyjz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2luxinvnd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2roysdnjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aglfxvvx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iucqbunm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtapnmeh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuneygp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jltcvyfg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2efjjcgml.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvzhnah.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nruxmldj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lijoeexf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weyeqhou.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqladheu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2woylogwr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwnffcr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxatlher.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpawxhye.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkmdmkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noywkqrp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2logzgoaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtptkag.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwibeor.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxpscpu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2koxypucp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2equlijsc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwilas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdtouzf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdslmdqc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnadeuk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2otqpiyeq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2betebfxv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdbbykd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdjlehd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kwliusem.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyhclto.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtbhkqh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzdrrwh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiuikyb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avkeepsr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atxdylat.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eiziubam.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xrweblqg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpxawcw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfktkvg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzeebza.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uksqpwil.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynajux.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wicxrocj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vazcqslx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeuednf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtunpxvj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2glzvqwbp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2idpwwbcx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ygppwrjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owmnixin.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvshgkt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fyshripk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdgynd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjpdfka.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzdmczt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qljvdyfn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuwjxqj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdlweuh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wfipogqw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2asfcdlqr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cpepagks.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cdglhpob.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zxflchre.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkjrrkv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbklaep.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpdnncn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mncxkptz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gadhhxae.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzwwmsi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvnbeei.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2izlwfajv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbfixwo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2korhjtmo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2faezyuty.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uycddwsq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhahyra.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpkwhga.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcuciuy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nwphuwuf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2htlsnqnq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgoawcg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2llnrftqq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2csmvoyme.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iwetozju.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xisskcrc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrzefbu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zablmlyt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2guolvlxv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ownpyufd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wezpjppv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hondrgft.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkrzdlq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkqesml.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lafsmipr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqqpxik.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kttjrfwi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdyqgj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkjxjmi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rifoutyn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtgokjw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfflmfl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rryfabve.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxrjxhv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2poucbmmz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vzirmske.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhccdnh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbhevc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xyewxtep.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vuliuwpz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oytddxet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shdpoeeb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwgwlox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izpdnrik.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpayykex.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfslxzp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwdkrss.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtxtifq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebciqfjl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhnbvcn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjqefji.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmebeago.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2htclwage.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2djeekcdm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mabqiibh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thopohgv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aerrlhji.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpjmftl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vigwpcwt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjedjwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgnaqm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2immmwent.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2usegtyma.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzmibbw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxukzqto.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqalwfo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kocedaad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrhhlzo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2npttbfnj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoebtji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgajyil.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcvajan.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqnjsgo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuwbfxk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfnocbc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlabljjr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmoxwbc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uentcdnn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhwvzur.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oceahkjp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdjqnfx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2luoweska.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2emlstqvl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2frmkzjkx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvniabcl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhrsryl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwprjyg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iovnvekg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oicitqhh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lzysnfll.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oroyooyg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhlkdtu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifzheib.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zchyller.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpmmvw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtowkwj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxejkuaj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zawfandw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nthmtujo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jadolkwv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utvprhnf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2adamuyct.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2heitxufy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kswyxnsp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yppfexol.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cssqhclc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eplxungg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrdjbap.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvipvq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuofqqp.html


<!-- 参考信息 -->