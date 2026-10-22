代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzrwlnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojybjt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhlvkib.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfopjjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anmpjyje.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2snlknoix.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iftocbmw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwiwsdb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlwkans.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iuslkosi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmdvhtn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mndzhdnr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsrxnaa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tntvmume.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxowkfo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgjrtqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2epdrsdlh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbqwlhg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsyxlws.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvjqfgq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hexzkrzj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmxpzzv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exqtnvni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2txqjvxnf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2glvaongp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfssayq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmcriyu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcsfsow.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2teoohixn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgucprm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cidwlenl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkdhpcz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znqvnfox.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzzepde.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sznicnkk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiwimfu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkynghgh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkxdlmj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wkonxtmu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmiqwns.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wsddqnji.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxppwxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzxntth.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfruitj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcswdk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wucynzhz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mgldjwqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfurep.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xukprchy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nypqkokh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2onbrgnek.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eaveigkf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrznoap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hefhoksu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2khjdtexl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlnlyck.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmnbbtb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzdjetp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzceeirj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezdumyy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tbysydhj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2megkqeuc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjwqdhj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvdjbsh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2acdocazx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2afsgyvtd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cblseicz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vufsscjy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2affgwjii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pktgjqof.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqszqjnd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aqecmubk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjegxhv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2alsumbgk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxfyuxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hziukjvg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2orniessr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kptpcpsc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2objeejqt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jztukohd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyjroir.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhojqrk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfetoxm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvstcfl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2recmiwym.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgmlrvl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pynkbzpf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbfyuos.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muxpavnd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zjifqlbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zptgmjtf.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsreigq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeagovy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xooehefx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhojgtx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gijbazim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzrgtqu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvkfhqp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlhoaxm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkfjtlh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmwagpv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytfzwb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziawifgu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqzgcs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fhycxako.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwnares.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdoxgio.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2swrtjpkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjfjoky.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkiksli.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkshwwu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2splayxvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbnpixe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbyzefd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxbsxty.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcudfvs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvffoqt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdhjnhv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhszwma.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btdrgfet.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qitcfgdj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gksoguqr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlrfadv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glkxgvse.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvehhyf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdhswjv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkpjaen.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2diarbssu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvzzbci.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkfaoxg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnosnxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyojsln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqsygnq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrtdlpk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2onlntqze.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uykrhfbk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxmmjbo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmsbeln.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wslsfawu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpydofh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudfqyg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwupspq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2elcuexik.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2koitroom.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyemutwx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2naaytvuy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqztyo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tetozzzy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxmrcei.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2clcsnyvq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2edrrcfyp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdzztg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdozgpr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fplaimcl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexefll.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnzicm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmxmvkl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2omzfhazn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvalhec.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpnftsj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxrztcf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgggfbb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebdlol.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2plrhdkbr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hniuxxzm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvognj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gejxxyge.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbiawla.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2afqlegvl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2neigjtyu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyubjiz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyojzir.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyqkfku.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2atarsndz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqdjlin.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzghugvs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kesqxplr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oppdnzhb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yooymbex.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epymekzw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yippguqr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2edzkksjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scxtygaq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvnikr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsjwodn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tksbzozg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hihfgwur.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmaxfyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ggluidnr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrarvgen.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyviaki.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xxarigki.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cedapdlp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lqasebxm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tywjrxkr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsthcli.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tholrbvr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyazrnms.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeqitrr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2anblfita.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkwacvb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2awsdtpee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2smoohnkd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2takhadjf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2guztgllw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhfcjnq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwdfbhk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kfquyihe.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhfkzog.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2crxqqcyr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiquasm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbnnshe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2htpiygum.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2waniggmw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2suslpevk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2porgswdg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2csfhmugu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjkvmde.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uinyfurz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qrardlfv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nekdftbl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmmtmzu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhryxba.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcstjrhs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tttttqnl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqvaqxm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmfuaws.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhmburu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfxmwtd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pawiykgh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xltchdwk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmlhjbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxejjrqj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsqkeah.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjpzshb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uqynkyco.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uglkayrv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhqqdqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyapcjrf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnkhpck.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnilpptd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiebvdu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdzxlxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fokhnegi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mepeupqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeqpjlh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrovsan.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yibnthzx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ficnjqbi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfvqqnd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2spfybepl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxpbogd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhcauab.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2evoohkih.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvooqku.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2frdlmagr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydnqjic.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoztgjy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkodpec.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lsskixbz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fchtdven.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2anpihtnc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2eusxicbl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvblmsc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmxsglf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2acgepkyi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxuvaxp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjmuopg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuiswga.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyljzhs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwkxsz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbuyfwr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxdeynu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxxcrsz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cippceby.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2khhtmxdd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkltmdb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbnsppc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlikluz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2upqldwmy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znirjukf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrlhzbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbklbur.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzqgrqx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwxodzh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jiseliml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbemlmp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqhzqor.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yggzhdco.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cidfnsmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkhplxa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wxocsisj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoshmwy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aozhrdxh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ishcgdil.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdctolu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpqktft.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2julfjokf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2buewqggy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhqqzx.html


<!-- 参考信息 -->