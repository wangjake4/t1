代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mblurlmm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vothqjme.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbjhcrz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacmvjgm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nootyxew.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbbtnga.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2broxxeue.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2twchkzly.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhnqch.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpivgwa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2juazbbqa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdohkpvv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrursqo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qsktqqmj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgbhzlf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mddwonoi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshqrgcx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuxopgo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdkwfby.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnvnciz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frsawmou.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zspwskfj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxwbzli.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2niceyjzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2luxmdozn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hscattct.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhwabp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwflyden.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dbadzdqt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbgwkuf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ossnqxwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tixjdggn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlbhngw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ooazczmv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbclrcdv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkyufex.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yarshjyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ralimlcz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2deyqkpsp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxslekbi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prjlnphr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbbwhjp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uexxsuqn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txosmwfm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tncnrjqr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyzwiuo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2arlemell.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoowgzm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbidmkn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsrpkoz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csyykkgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkyexmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2esomfzzb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofztovhe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlnlgyz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvanzmo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmygvvk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kggxkgah.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2erfravmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfqymx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqnvsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctvcui.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2caxtwhlv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbycjrg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tixuyntw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvwduso.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeroezji.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrevzcw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2avjfueyc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxqlffw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjlmll.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2puxqmsxd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbaelqh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2opuyzskz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lngsqtss.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsobitmg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxvtkys.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykmejy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnnuoyh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgvwxto.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bylmkzct.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqdvuld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2alprkwlr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2azohppxh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hlphqtfp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdvfuih.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgriard.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2inljjmwb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tphsirbt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcbeptk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2opztibos.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iivsfbus.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfexegn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzndzeq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhpcemn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imfgxbvs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etywxocu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqpkqxg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vujuvfkh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2txwvkkgr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dijkknik.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvvqnst.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2knylqigq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wozhotfv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjtpntl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgnxrbo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etbxeqpc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2caoqievr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvmvco.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcezzww.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvwfdog.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czjedknt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdypuwfv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uetdquzz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2deolavfz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfixloe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzspvlg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtqgzac.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrelgyo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuowcsv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlevpaet.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcgoop.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2svmivrgn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzfgscu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlubblll.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2arlqvnio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2plrlwnsq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiouydx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdvpqlt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oidwklly.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxseam.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xxquuuey.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjqonri.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvnopzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2athwqhqe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2albglvhk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrdkief.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2odcrimpb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jwssjtka.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fucybzai.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgigfr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fuddttdn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2shznhkqi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qilgsfiy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tviordpb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2whlyffbf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ughsjnja.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyfrsku.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cfabmctw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2urmgubcu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jiipcktl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iodwence.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2krdvoytf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2neffsvna.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjugdjs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2meppckvp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bfplmzoa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpclesc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfupdwo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxodoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpzrspl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nouuvlhc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wanfopwe.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbqqfrz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mrinzhqu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwkhefj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvziwa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nrptivse.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2savsjyrs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2arfxwyjt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2achxgiwk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrybqrs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgixpfm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqixuti.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csmtrzvm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuyfeeb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xggjlrgc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2entefnnz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeryaky.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wspvjtsx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2janpjtkk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gohnfylc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2khhohwfp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lkztxlfy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2apyemsbn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjvjngm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkdttwo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdwqssz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jwneudeh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wphdvkjm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnqhvja.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uoipzjli.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vjovxuam.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkgoshz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpgonq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdewcjo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xklrouxw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2stmacsdi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2alqjyqlm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wieyrpdg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrzzanb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqzsmtw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpwfqxw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfeympu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tiesjyrb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2krexylmr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xhobibhg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqvlicp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2outemfug.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnwueii.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxivtrv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2szljyosu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzaphyf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbalqed.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhofxrh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzztjxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rywpchbd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbtyjlc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmbkewz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wpobqnaw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwxmvtt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzbcigi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxrwjlk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zobbavcp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyivutx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nupgfatz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxfxkkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqhxlxa.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2puiplkay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghombskn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myxhzhnt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xatsqxln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufezdejd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrcbonh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbpzbyp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqbrgtw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhktjkv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjiljrl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqeqrxj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfuaxr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdtaazk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiwqvil.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mczoqqae.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgnssvj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhuqcju.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2szprbvii.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2erfxyskd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayufjwng.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rtksocjg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2arewuohn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2raxaxxuj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmchuca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2usycaulu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vosydjvv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2itfbmmun.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmcwqfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqekpnv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2idbuqgzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahukjgeh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmoezgl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcxdcoa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrkklwo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbbrtjy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbppjqu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsilgna.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmldjac.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbwjhfg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egybomft.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoisviq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjlkdug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gacjctqe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtutkbv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgjade.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jciiqvsx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqecoif.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iygwzgmg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkfgedd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2navkhewn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fodvozrr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjpojwe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfnnahy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfzqjsz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbablcbp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xymcimur.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufijhikm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xinvczcc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejmdctc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsypzsu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnvngxa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tukbbqvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdtsxu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aifmsaqt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jevjdydz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oirgujoz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbkjuew.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbmfaog.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2usjpwifj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2firjnljq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunieux.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxsxcpa.html


<!-- 参考信息 -->