代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbutmoz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfdftnx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdqbtew.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tksizpfg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjxgnd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xileiyeb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzzlmks.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2aitqliva.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2craibdhv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkiqpqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnstwjc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyxmtdk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfnozn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsdupfi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxpwqjf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnhyzvl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2exgbzkkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafmove.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvfteqf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eputbamb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rezvngxg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjultdh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjipunxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2arqpoebk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbslngt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2foyycjvc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxffnof.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfznbbdg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgajhjwp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeftsce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiljuqk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zxstknzm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjeztro.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftwwxe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgxgmcn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zlahgckr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuethmp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqzaktq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqvbhcf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eyotkjew.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzekylx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jncoovai.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjyxvlw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnagnmb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gykktudr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dezrgkcs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vheojpwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sepgkqpo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rydhpzyj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuhterj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2quaavjua.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2uugopduk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiqqnkg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trpiknqp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sduddhyh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idsonetc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgohtghh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apnabmkh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmvjjjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txpfvoaa.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2emkvxzcq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlekirfh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rynlzjqu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gianewon.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsbvxes.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxfnbyj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcrmyly.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oldtquwq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivryswuc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxdcszr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfmowwn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hkafqbjl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuzoija.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjesywd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgpozsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxrqltr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvkgslh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whjpzjkl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaxuaqi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pilxkctn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2awfwejlr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2peokxcmt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aznemikp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukugjrub.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ovofnysx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tebfktce.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcipajf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvwayci.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfawfyw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qklpafsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwpbbrx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqqejjs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kiouembx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvojckg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udypbccg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdtlvsi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtzcgjm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxruqchy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdwakth.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2baxktoyc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejpuke.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyyrbwi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2himwgncf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbntzcni.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2asdsgige.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fherivgw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uspprgvb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dcppqjfd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gydkagch.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gjejtdvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iivmhusc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpsqfte.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emuplnso.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hczjmzcv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2luqspsxm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zawgxxij.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etmqeild.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uipnxmgs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmzuypj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aczxdeow.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxkecty.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wroyeoup.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqktczo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjcrqnn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guytbewt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvyyfjl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocijjepm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjhqcqn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqblkdm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtioryd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxsdzjq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sszeahpu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqafnxjs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqatfpl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdouduwr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwczpbhr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hagepfej.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rbafpdny.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsrlekp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuhitkg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nuinswgp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzchohg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2duoamzdv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kktpuslm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvbsnrd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pjddmhmj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhqsmss.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xheksxfo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfehlba.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlhbips.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfjdsgs.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jljvyoyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qphqlbrq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyymntsz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuiosym.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omloxate.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upviaotx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zxinnlbo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gbglihng.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pueljslx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgngit.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrdcfye.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jocxlhyf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2itaiyprn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdviqxja.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbyqgnc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azjloygl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyazbotx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fydcceje.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pewdutsv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aiefdgsz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfknfwr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2udulwray.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcpkump.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcydnkz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yerswrln.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xupdsihz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhiiiae.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpweepr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qswzytae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfxyco.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xywtgreo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2feiobvwb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtdvia.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hbocclpg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxtmbhn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjppulk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvxklfm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjiqksw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrzcovr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unxcvknd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2svhfeeqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nnecvsfs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2opghyojg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2woavfoni.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmkate.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jatwbkxl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhfqetc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rnumdpne.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzvrspt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yecwomqk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwwtfat.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qfldhnfv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxtjzop.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2navbkaat.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhngqqzv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqitvln.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yblhoqsb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmubyrd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuxsoot.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolgvssd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfupncca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnwvwaj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjxivvi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mcavcpan.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvlymef.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irzmlmfq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfwdmde.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fprmnvfb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejdlpk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oowwphtt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oebadmyz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkhufmq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxcpjso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpcuvbl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aafxsary.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoxpmcd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsoozjq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lloiidad.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vljtdmzg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtphhxo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtejpib.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hryvxzhp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpyupyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2knsgruzg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mobyhqia.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfopstj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvdlbxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blgmowlm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2goyjrwwp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chxofopo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnubgkll.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dslslgwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oasjpuda.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzviwqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjdzwsc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcejclxj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kfypxhva.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrgglhw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxmcmdr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2owriipph.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xirhbtmv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2glcbyvmg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqybmepp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgimvifm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlzlvtx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyokzka.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzggljr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvpukip.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuhpnjd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeakiyt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mtymxqyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2itelijej.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mlumsqvh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlatusd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxcgxvk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vthrmfjb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiclfrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtwgduz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2macoxwgh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyiorlj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjgbofg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rujwvpyg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uovsctly.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuversjd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrdywvq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2arnqsdea.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkbuheg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2piygevnu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkvtlhw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiqrpst.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaolhqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeyqxzz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2czawtysc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezcyxg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzzdumj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afuqtjaq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yxblakjn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpyzzpa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjjlelc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2curzbzge.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iksgneps.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuoagbg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dekvlycl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgiracq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iyryhuvh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfborif.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjfmcze.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tljimkzq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hiknevad.html


<!-- 参考信息 -->