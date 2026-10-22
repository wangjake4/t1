代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zemajoxp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgnrbef.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjehfzx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpdpehs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbwyipi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdpyqpk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlyvza.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyizyzpy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2laxwpxum.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsnmlzw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaisxul.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ombjdgle.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zosrrqdg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oisyngvo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exdcbnbo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rxykstuj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdwkcow.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkehezz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kslcvxqf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkakxjj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2syagfnkw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eimqzoht.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlpawxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxnliml.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hepoerqm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2aiduuwan.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zluovbvk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfhmtkl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2klduuhcx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cntrxagx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbyvdaj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcigsvw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkxdvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlfpgaj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2txxrjcjg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohcpmhj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaihzuy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2utvvmbut.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jotasjsf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2laviauuh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlithuf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsxxun.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kguxebyk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2difaszsh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfpnqvr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjjmuzu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwrnlvo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnisara.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrapslj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2escxpugf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnlikxl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdkmpao.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgepgpn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfczojap.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2givkgxnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbtdwqw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdumers.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvazmzp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ggocrqrp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvmviph.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcnboaf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpuhvup.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyikslzz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2caltttgx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdthstk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpbaat.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoketic.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2petcmvzn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzimyj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cguimpza.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2avmlaone.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqkpnoo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhdrvvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iufpeuoq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdqtdeg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqgglul.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2arocebux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvbtcoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrxvrcl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvvineu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmtymrx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nowfcbuh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sncvgwky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuzpkce.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uamipxqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrhwmjc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ednehsin.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrmrnwo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdinugi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2efjcjhcq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqcebwz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjugpsma.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qwylkwlm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wafgyhxt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcxakkd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bioouqbo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nueiznkt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pikuziut.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzlopzk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkayfgs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbowqup.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2reriwxtm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zncazwpm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bngdpvts.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaxgulb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyexmnu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvlwgq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2obxtlxzp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wurgftfq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgvyqrp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2guybhwsw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhixcig.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyxwxpk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxldxui.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rprtahht.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2geqtpxzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrhifxb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgdmxfj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnggrqyj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcimcbds.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdkfpwt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgqwdpb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eupyweof.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjekpaqg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfnrnxb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaxcnll.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqzdfl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2biikduld.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxwpcqg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mulgfeqj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2volgmxma.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqibfmo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhxrflk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtsycga.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfqvxqf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dawfyitk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpdhue.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2azdgxrur.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zipitoqn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2doptypfc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlatund.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmwaxo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yujqunkv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2foaauqws.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2knszmhej.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gibpqdtx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrsrcxs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmonlbe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcmsrlj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsfdxpl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2igawiljm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zydzfwhr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoifrnq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuigyrr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hikqtibp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsckgbv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqjpsil.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ilershru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eaubeezi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhymrhx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2drmgpbns.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlfianb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnokpug.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqwucfm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrkbmfv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzpnudx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2psyeqncq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqolqer.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adknxozq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2emofhwao.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2casxxbnw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mnctiyrv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwgoqvp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazsqkx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmyokv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpatnve.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwsdijm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmrgflu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfmqkg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmyomef.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dbucbfam.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjvbjno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fblbyxvu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iynyfxld.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyhvinr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnbqnde.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2estsyelm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swvjxsht.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfjwndq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpkqcsl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuminhlw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvbvyaa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gjavuicq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zllcvvkf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwrxnms.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2emsccrcg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlqfqyw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htbxztvg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdktgxud.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ctboarjg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtvdqus.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cufdsihc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzjugpa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2keqtudim.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzluxci.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qemvdogx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2easwkwpv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtjuddf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdcocnf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmhxhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ummjhves.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqsuuwh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2idddunsg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szqinibr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzcuqng.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeppbux.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tasqwwno.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpwkvvs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkxjqwi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgqexw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiobkih.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfnnnjw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hpslikje.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjfhjzp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bguvokvp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2coouxjex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcocbjz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzkxbvt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjyisqh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jofncvxh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjrryp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhixnkk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgcnrfx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmyzdhe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hliuaywx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gadqcupp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uzduectl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvehujj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfcnjpn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoahvda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmapmpr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esrpgwkb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzosrft.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqvjaro.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2npopcoca.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbvlsmx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeelnqj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ryflpghq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnwjww.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2esaendhn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xavmsjzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uiapylxk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yypmczqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weviswtg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pykktyte.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lycgyhwe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjisdqo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbtsnb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pijibctz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxastddz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2votfevup.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2awowuuds.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxfaotf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewkkro.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnryczdq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2riqmccou.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydwtrg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vksftlnh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oocgnjec.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lemlrqyu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vphxgjxq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeodoma.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2usbqbosc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2erxddyfo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bftasyux.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vczsdmhz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2szodbkbl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2geejpswa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyikuvp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rirdnxqu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxaivvz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kimyufkd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfujpty.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxhnjfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vudifjuk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvohwsmt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmntnybz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzhsafs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slovqzmw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoixztj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrjmtgv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knzugqit.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxltfho.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsykrrqj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoflhhv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqubzcw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwqkyxw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qmodsugh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzefuy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wfawjctm.html


<!-- 参考信息 -->