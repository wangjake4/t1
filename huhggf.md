代发 wailian999

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeflgju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwzknzb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvnzuds.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjboqkq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmbsulb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoxpfns.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wvigaocc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2aryfoxjs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swuijzgc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjysanza.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iygltxxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtrlfjb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzvwpyy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2iugxoiar.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkxlplv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krecbbnf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtnpgod.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bcafkxnf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpmuiem.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iraqxyhw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bygxwwmv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgtbwqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jocazkwm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zijoenkm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heoeiykm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2byncncsl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlbdsux.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dpltihfr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoszrwu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqkufoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsvuxcf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2edeymyoh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fkavflbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wumdvlne.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vttezabg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmspwvv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvjzcaf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kziwvuje.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrohhfs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2slirgrqm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpahkwx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thuyxtnd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vytftpwf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axrpgleh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxrtvpc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiglwbo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qraolsbr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgowanie.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2htoemupr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2espsditn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfgpikb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwinybbs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2locsdsty.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2crxloxod.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxyhohh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikruwbws.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwjwrag.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqbjihc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lndvgwum.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtptfds.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2knrxoals.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxzbfdx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yywibbpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzvnjfw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wuapewsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlqpypd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2smjdcggl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2opyzkmyh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwbmdvj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2klfchlvv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxmffnj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umfjngwq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmdjjnw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtssxai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuuxafc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2arugiokt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgxpxnu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwoztbb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgwqfrc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeuzspw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lttnqigt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jimjlpam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egdgidew.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbehvoz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqjvsil.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uldktcns.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2emygfrkz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2juikvyem.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdcmiwl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2erpkpkkn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbklzjuo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyckycu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2coefylcr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmdjoeu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaukwqd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrcnhim.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgbighe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cohkgapo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnhdrup.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtpwkju.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyxcgwx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqifmjb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kcugknny.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2calqfoqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpainwz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srpcyryg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqxoakp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2abjlgpng.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apcfippr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2svyjoqrn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeeclbn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdsldum.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhzordz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmpqhym.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcsevix.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eshsobaa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crrkfnic.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbeppvw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgkadrb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkvhmwr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wranpamy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2exohfaft.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jurisigx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2daqqsdws.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mptfofuj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtyljli.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bjawkwln.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eawmimwf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbmbpze.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2swafohmi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfduzhx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjqnnrw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buryfkzj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqufnlo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2splfbwqa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2whnslhli.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuectih.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfqaiop.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nuatrwrr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gtotulre.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dflkhtfa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aihxrzut.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kobhwqcw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ethjzjwl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvqtako.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbnrdit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2damvdwet.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2plqaknob.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpvohny.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqsuoqq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2njkeibxz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uglpsiip.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbyqhmu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xquthplh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqseagkq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2coyhhbkx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfxdfmr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iegtkgvp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gsytiqek.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jiljgjpc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2grhuyllf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbpksrp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dwukbydi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2myvbiimr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uizhllez.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvyxcpu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjuflbl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvignzg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2knrexynh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eabaaxea.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dboalbxa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2grgpqyqr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaobyxg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfkxslt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlgnwmi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnxpdha.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyrvvox.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwxxjvs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoyngzt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuolrpq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xuluuqtr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvzeuwd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ofygifxt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fuedmikl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvlxuru.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqsfvua.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcdkugs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wtebctuf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igwbwdyb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2byajqbmm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2glalvzgp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2quqtwpdy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxfetw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noifghjh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxzmfzz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nktlpkjp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jsphfyea.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbyzqxh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzvilzl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvsjimy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ycduutha.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqotcyge.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaaboje.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2brqutdhn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmwqxob.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvflzni.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrpkgii.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmklptj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kynfrlcf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdlbqkv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2krazholf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gypdxyly.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhqvjex.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrdkksb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqqevbt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpyeyxy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxdjyhi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcnubm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfxkzgd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjcrqoy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fglozvao.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnalasb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfhjuas.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2statunhx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoslegj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgfsftf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbgckzo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjaqvre.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzecfjhj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2evhkprpi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxjvwjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeammde.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhljcbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbygrsrd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsmxqhi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2exhdnlpl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fixqwnqd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2opocgpnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqntke.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxdjzrj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvqxyia.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrcvers.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulggsrzb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2srnyipor.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwxwlig.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqcgutc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwufwaw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2shuujxtu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwboraba.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cojgvxev.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcpkxzt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfxsivn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqrsqig.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjgsqod.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdzjwc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhowgcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpekmvs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fupaerwd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdntkmno.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzvbpkg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtklucw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhduhjp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tacvdxiz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkjgnka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2woakeqql.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sazlqgpd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxoqpn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfinlecl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhbimcz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drrxxryf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2edopfjfm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzhbyxw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2irkgqpyb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irezqgxp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtujlxy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkotaim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxieqtxa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjccwtfe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiatkhvb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qqihdrbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rucbvyit.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sypgrenu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlykwqg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tefrgnay.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhsdeaj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xccnlwrl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhhhddv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2djsuqrin.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdqmxki.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjkokm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsoefyd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwddefh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hilxfsxz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoshepvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcobayy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xwagbhgx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrlakov.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrjypvw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2npxvrvhn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2crerpydb.html


<!-- 参考信息 -->