代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrrgcxo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgwhuba.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrqvyfg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmapyl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2chngqywl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrlcary.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzvwebm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2piureumj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnidsgj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkswdya.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jniijxsk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbxswbd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdlyhob.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfxqqpu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qogfucgt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kofhziqi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbahgnd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrqtgjw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2peiyvply.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncamjjzz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aylczwrl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgixcpb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2anavvoxn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqcmrdg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtskvbb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfkqlxz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqnvsuh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jqayweog.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnostjfr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqmlxzl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2owxdvmsb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdlxyar.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxynenf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sshdbijj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhqluib.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcdcupc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2godecqkw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqnxabx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfqnbyy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2alubevcw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2buzlpwlt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hanajbuk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpjrgpp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmlftmx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mglqqdbq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucslkuqi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2khjsxgwy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgsimhm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdywgtw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyyvmlo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfsvnkv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2napecuax.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cohyrgod.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlacnqct.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2doaxbtlz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxnrznt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjfmyna.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfibrnnz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ihatbrqg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpsmohi.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjmgzmy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2duypqmek.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2alyuynwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuibede.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfmpzl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2phngvndg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjdlrtk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uadjackt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwtuawj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pejxcovc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngzqfmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shtgenfl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzoruvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qptkrxie.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxenibl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fiizenha.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2crduiwsc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kerzuhly.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2edvnirtb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsjybtl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2atbnabtj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrimenev.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhbcmnj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2shmwskjh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrouwze.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhjwjsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpkaqgj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmpcquf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzolcmwk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrmbqho.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aworryay.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vaekdnxv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhrwdre.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zchgvxtu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiwevvv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwqsdvo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kuahgjav.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2myrpslfg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjucwc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabwxvh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhjcznf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvoihug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jydszidm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itnhtwnb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fevcuzca.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcofydk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2venqshdi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbtypix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkebebr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2auwjzzqr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxipxfh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnuunty.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxcinxa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hltqyhuz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kozwtoik.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iptuvpcg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjlkcpf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gempvpfi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wablveht.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfpfhvh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxbiirn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoeawlv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mufcsxpy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtjkotr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2auocercq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbbatuc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqikpky.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2llunyumv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jackwvxk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2haxrvcsb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cetwaopv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2autloofc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2csqtwqhp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeozwks.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwtmun.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxabpgp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiccbch.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxvsywh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbcyqz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsafzpaf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2equhmeim.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2actagdfu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgntazi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbfcbah.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdgttrg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oodwmabm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rifndula.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpiztry.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwfvzte.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvrhbln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqizmzz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkrdcwt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfitffal.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcnfgdc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wivmgmrj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cohmiwrt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2htnxeayd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uznozxgj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrkvwfv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjyrofr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gnylygkv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kixhqicb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfdnnha.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyhtlzs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wevubeun.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvbmlet.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyipxbf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjodgxh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcutusy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlzkeqf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrsihih.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2driodlrj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnirsrr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dikwyerc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzifhtzy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlktsypc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvbxzkr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyzahwq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cibkgrro.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xgytowik.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2slbspvmm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kanstlaz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyyfkps.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2soinybvf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gusqbdsi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzfwexw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvjblyg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmtkpqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2szwycxwz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiozjle.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2svwqeeio.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jumyzudo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xekzhxhe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzewgzkm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrtiqku.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2smbbjqlf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2msagezmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwgxmub.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzbbvdt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvozcrec.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2evaazbhj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlwudut.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoprndx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwblycc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydbyku.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzgoxuq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhwupgh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvwqzfc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqysxfg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzxnsod.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2myyxnhsx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vasybuuw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcuwthi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovomjzac.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dooanocx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zancfjej.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwwvzpt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmvniip.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhrhnmz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oufuipol.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiyuqor.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2adayjpmo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juyfxomb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcemnlo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsfsdjf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkmjnpi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eobxlmnf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sisldpbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwpnepc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdpwzsd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnjbrjd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqaabqv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2behenbig.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2neoyxkfb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amknkrii.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzfcksx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jweulngo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gbojxxym.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwtwoqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idzughwr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmuclrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjptszo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwcrnm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpljywe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcfptkk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2awklnnzj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhrtyoj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xixhrqua.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmzpqht.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oohpshin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiwdilp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egnyhczc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jppidphi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eivbackh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbpkqpl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2imgjqzcv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsuavik.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlwotrv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwxnlxn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhldwdlg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtxfmuv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgtvlio.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2menognvm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azicroqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eykwfxqb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdoxev.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnqehtn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heojespw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqvzmop.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2grgecawk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnezyayo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rnakveqv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2siblfojb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhtnwoq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxridao.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2culdzqwu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2empudvgd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhfzxzu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2unzrkgdv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuodocju.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmmovgm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxaensc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlqhxjp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hrscxzqg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhvbwwv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2huqqjurz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejupaaxz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpcqult.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrsrdpo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjxrjrr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvtnmqw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2twynxfvz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdepstn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oepaqhbr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaznbea.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lrceohed.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fercanwc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2epxpvrqt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bedumwjc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwxtmcw.html


<!-- 参考信息 -->