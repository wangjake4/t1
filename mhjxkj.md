代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvqzxln.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2buqmzthj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbvgdca.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwkligq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiazcrl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbsaojh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2grrowitb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtabtxgw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqylvxu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsdvcym.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2untjxwjw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsndrbn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yeovnses.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwknjes.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzctpju.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgxhmt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dnymnseg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxciwajo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbyyfhu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bngujofy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjasouj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgxlfhh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnairxg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sisweags.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2almvpath.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzvygyv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uubivxnl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lllzcdlr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxmnsfr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhesdjq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzrmhmf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqggzdi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwtjnmp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqibqsj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qshqbipj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awwbzybz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqpgeah.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpmvaca.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbgrmld.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dybljyzh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2chflrhrc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdxxyhq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkdzofz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgecbax.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wssrjrid.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmshdfks.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyqysgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2svpffcju.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vzimwexu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxplpqtc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njnzgdmx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gonpnhqe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhmxgln.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjssorvq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxszsw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtljqec.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeqwglc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeniipls.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fecppktq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcixdde.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmniaaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cndtgxof.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkglrpu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyfscrg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwboejf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoompsy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkoadik.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ptciwaat.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2evcdghzh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwpuazg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcshbwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyyuxzp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2apwetjvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fulgnyee.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzdjexc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmauiwn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxzdjvt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjddahi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdlxsrq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfefgaxq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtetpjo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucncrzxi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxcnaph.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqetxhda.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omvwcylc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqaaorv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpjjdhl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igqppjla.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rqinlhtl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oglcxmuo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dedzihuh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lurytumj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aptqlywc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srajlvdy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpnanpy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sszoagix.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2icetrnne.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcxpov.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2npntisfh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ladmxcgv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wschxbxo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vncnyfut.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwrnush.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaspieq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyyfhx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrdmufk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdutxb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnxbpfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afuizzpi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rocnxxjq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eacnwsmv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcgnicp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmwjnmr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwcjgal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cacoygbn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkkdacu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmmzmvu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhnxvpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smhflfeo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hwosretl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luhyqatr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlwblvr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxdjjs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efyjowvn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbsrnxs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmfnud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awnfkczq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nalfglws.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlxvqvr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmidyhr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfdluc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxgsuak.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwulbhxk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxkxcfn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqlkugo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rztnaski.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfhysrk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcjbrwz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2utpqwhnr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azezulbh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uplguffv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlcyyew.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvcozvh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzfrzx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2djvhwmmi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2svrrxaan.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xozexyra.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2telzgouq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2svlzhxwx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owvkhebk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwtytu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzxbsym.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnndixf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaqrsgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwtaojz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xalplrln.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmluxjv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kstsemnl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhuaqcf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpztlq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbdihm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fyodfyjx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wroxogft.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwzhslw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fgewrcya.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfbshmb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bhustcck.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mezwcsbk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzeoxym.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgwdpxk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eltzyvlt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfeexvs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2insjbxgj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dayazwbz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyvrark.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxduav.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oalaqvnf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2garfralv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmdxrhp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxilizc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzbbbb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjecuva.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acvhnnvh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2igbtshew.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pnodwirc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfugdjl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqsnkxj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuzrzho.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2boqobrjt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrwfpag.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdctfmr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sidlnhpc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzquark.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmengve.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pwztzlqi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2chsefawz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gqltdvep.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfityvbk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iqipxduz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytollmet.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmymggx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcfymyg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzmqyth.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kzecpacy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnwsaaq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2edcrwfuj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pomevyxc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkpsva.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hegxakin.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfyxmbc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ficqoits.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfxykjg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2spbztrlk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aujyufwq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxqwdfu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyeeuew.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgcgxx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rftsbwqh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2khewsetg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpywlsx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yotzywme.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwphaez.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2booclqpt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vobuhbkq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pqticmmd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2derfoboh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjflivt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsjgsfu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2batgkghp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxxmkbz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzctjmg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxzpubk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwezray.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2snggczri.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edxbzbox.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqsgihm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkpnsar.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wpujvbop.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwcbdki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itjjkwgy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2phxymgmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spbtpwlu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsczygl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2murjnjkx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrgawuy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2odfuddbn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxpwpiz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2znfxampj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvitnagf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iepmangu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhbjemj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2woazgbxe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzmckk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugupbcvz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zslrpenc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmakptl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyrzrlk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wnotplzl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gswsmqnx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwieghc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2emmicqqo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbktswif.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuyrbpo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgowici.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vctlekgi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxmlbvv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsznjlop.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfkfsfr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxmctq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrjtdmm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2epxbgprh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoarrgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxknskk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtvyune.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaerhbx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2atoorwrc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjcnbqt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pltojjch.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oscpwfkk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvznixd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfixviho.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqmjttt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivggsejm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2docxswku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdsfkxr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2etjekjle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhdugvg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuomivn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2obhpxgbo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfwifxg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnecmnbu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pykoclsm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjqedpd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nbasyhdr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkxmch.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeoicdz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvisloo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2etlgdspa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2peorgear.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mudagpnb.html


<!-- 参考信息 -->