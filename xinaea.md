代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfhlvvt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cnybrmhv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrokbvn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jbllokcv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpymkvma.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2owgzqtwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkgudsu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgacugo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuqbfuk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvvebnl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdizljp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2adljrphh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpdcitx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdmubao.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfuszo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhijqkc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeggbvp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyskdnh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkjeksb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2readshgm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2eihdknhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnuiqkm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2diixpfws.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnecqyk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucbrxim.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhyxexh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhngjjg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2arekcyie.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbqdfvw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhdcodc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oanhuvsl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hskityrd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjjanwa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wangdyma.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jganprsq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mjafvogv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2skrfnlvk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmhvjct.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iannwpul.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zevyfseq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hglpwgec.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjkbafc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrgtemp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oiryzqua.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmnleje.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qgczhzxc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hksgcgpd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zjedlulf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2phmnspoo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjhjbda.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twwqzklx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwugdkdz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvcvxlj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqngdigv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsuutgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdolphjd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2keijapmz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hampdbrm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nelsnauz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qabbwafv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnmhejq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jqreceka.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrremib.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mabifepf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2woszbpmj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gtomnbon.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wormviiz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2llwqsvvt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oahmfclm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfonnrll.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sppjqbdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmarxru.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwrdhhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pacngdez.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lksrbhck.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kagguczp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zzojbpou.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qmahnmam.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwxgqgh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjoxwrf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mknrjonu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwihorrj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkapsoej.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpyqkvm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvjeyfg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gptxgwru.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stmnwkfj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adfaypat.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eugtwnvg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2estkcprn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vijzplxm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfosrai.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pndgnezl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzgzyt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wauntjwy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlrjcrp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrohoql.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aipfqesn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhmscc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2usuejjny.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgwejut.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yawnynxt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfpiwyc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnljtex.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xehurfkk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2abhosclw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woiircto.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnptkvtp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poqqvpns.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhgoidi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdovmmtm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcnypos.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiythuq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsyidqv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvbihui.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhqcbsc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plxffwmz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jluncagd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuuhuiu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2owcykxug.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qihnaxgw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfhdykc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxjbszs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dufzbwen.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwsktjv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxkbgre.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2muimxyor.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2phaiqxcw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlixzsqj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmgsjbf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnnnaxu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmmlagn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhsnmsk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcspqz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuzpjmm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrfzpmn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uuubtkzd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxelitd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnqcca.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfknskw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beepjlmb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuesedx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcggzqyy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2stwgqdan.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuvjalb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuwszrh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2shsbhxpb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hijvdgmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2joqndkbu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqtdbwq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2thrtnoxa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uchedyeb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmixbyca.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtedvyp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjedwrj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzbduys.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpydsgo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgfedht.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2seshergz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuijkam.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gaukhpog.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwpamu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhonvqaj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pootkmes.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zczpnfwz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pcszisib.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aascuqni.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqeeune.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sljsnatq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyljhrf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfelyqm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acrkyudu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uutxjlwe.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsydaaiy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhorsjn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etgvhlky.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xgocgpap.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dqruqhgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzzzjvv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxazhcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hicoxoyx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhnoble.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoojkxs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbrnrkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcwsgqj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzodutce.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2seamebgh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iyymnxxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsbycso.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2erttiuts.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ljprkkmj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lecclhao.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2plfovuyz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vltzsqvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qigrjoho.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llcfothu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxqbtm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrmthtr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2isnykmrn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqlwtye.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkqcyiq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbqtulc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpjrhxr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiurdkp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yzndkvfw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xvweecpm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhemeat.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgkhfer.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwfvira.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpozrkv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvwgqpq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2youhlbia.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2auoqtzpe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdpkrfa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yahsttmu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qeorcurd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2baenoghh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqdzwxd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpbemsj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpjdgfm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2oghrrins.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwtxjrx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtawmfp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwfelpd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlurxry.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeabhno.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxjlbmt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzudifo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zipnfnkg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flgtqogu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuqreie.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtqpbhh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2arbuuhgc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zswgaaty.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jymaqlpy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtcxky.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2siqzohbc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuklfdb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfhkzbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyalxkiu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qddtjxbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dftrvrwy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzwbijw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqyfawj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seiwxutx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhavoos.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbsboeo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpuadcc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tebxetxz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoxhzsu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2psiednel.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kayyuorq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmswctl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkawkml.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wosbgslr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwznizk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwhdeyd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2leutrtnb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbovtls.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrevmdj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzgbhmz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvuoilx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpwkhcj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atewattc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2arpszmfl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnyyxlb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2peujxbzd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbczuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aknsubhz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdnnqoo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpsncit.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xvytusvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tefbbmme.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2prsdsjdi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmoygks.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzuulyf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnqsbke.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlcsccf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoxgfju.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2njabxpja.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwussmty.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rceekxoe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxzmorj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkuimps.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqbogif.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dpngwwki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2czrxyhsn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeovwhb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxaypbf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwysatlk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvobyjj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2soqhdhry.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2itenlzvk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrhlzho.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2towrpdtl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mlspfbbx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfharcnd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlekaus.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgocysp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqpxbbr.html


<!-- 参考信息 -->