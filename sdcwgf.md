代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tkovygax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2whoaoqmd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmfmwzm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbvjaic.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfhgbfl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2obmfwdeu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2deokzjzq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2btefpzjy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpboqgm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lakuykcu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcnaebf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbckqwpt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwpgmk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaepqjm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhkefus.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nylxojme.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfqksue.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpkgier.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxcqwh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzbpgos.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrytbvdp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mokntmae.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhkbxlb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhydaam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqdjncu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohrcid.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdlruco.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jqolmnnf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqhztr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvhfqhs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pnigmsjh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzyrsp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2orptumbx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2myfcmbdu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2extuiiwz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtqfrum.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qfstzasd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjnasu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvohrrbt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkooswaw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfguwji.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trrebket.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjcysoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeecidgg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdlngqv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfgropb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoxlhet.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tczdowsh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sboxnapa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiasdsn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnyyxec.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2doaicepw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2omidqvlk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvroert.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxodqfjt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xumcmcss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqaayxd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxqrevy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvxbzcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kywimbbf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rprpcvsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzpfmim.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2baxqtaru.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkjhwvx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvkqyvu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcrhfpc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pukhpaww.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzzzbbb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nxigkcab.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqkqtaf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcppxhyv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tswuncng.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoqwsdd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgnsayu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjshmkcz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcndhpsd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqqwetb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2duydqkfg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxvnbdv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcennbas.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orwsmtez.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swpcznug.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyvsmiy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjwebk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdjwwzg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mesniblq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsmujyn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwtygqs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkikure.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzssnung.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ryquydfi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eisvejxk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtnkpoa.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yhozqcuy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tokescqn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfediqzz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqtbirm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrjcndt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzibsfo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqsyody.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rywwmgau.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qggdkoyv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tppkvbpu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivmepy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akkmqfeb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqzmbf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjthzmm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lzryfigk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsbfead.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eydnasbn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpifnlzy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqmruqn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2clpcagyv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxtrvyn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yievyozw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjqlvvi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdogghxq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzhpbr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiljjii.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jagqunhv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sukxfuxc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tzklctdk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcvipqi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2koraufvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcevvnit.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkwtbuu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoqcakl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gthjmegy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxgzmxf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kobwtfjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjhmpvl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fduozlzp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbsclqw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwezbsvw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2chandepp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2shrezura.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lihtaodp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfyrnxa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzukkrx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxahqyjd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzsxslv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrchbrj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqlhrot.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzphlnz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyrrjxy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hlooznci.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fehdmxgg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjssnue.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2chxavidr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yolckrcr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udleqihw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esafmkpt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbogvzj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oioawgny.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzynddj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwcbugy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcjgocy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiljemf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsknsjm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmwpdzc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aeerncan.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgthsdte.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnmnzgd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyufofcl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzmdsaj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaikztw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aezkwviu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fruejrxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eciabjvy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnebavt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abeoblke.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2phmbtuhd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2scydjqhb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydgnum.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bndmxnps.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqymema.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yimvxqnm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zqztskkz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dkepfybu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrbkwdo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gfygdpdb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcjrtsu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbufibu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2trzvjmty.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uifyvnwx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdryxal.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2whlxfnpy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gwddaeal.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjebyfj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zctyyaax.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjxpxhn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lqykluwc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gpejgtib.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxlhmy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2awcfrxsx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmulfyfr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2thfcstuj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdpkpst.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2baxzjbwq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wndnlavw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeehhod.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsruccif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koxmkmxq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmaougz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ernrhfao.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2brsxbzjc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcfmcbn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ftciduca.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkqsygw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fklmnlqj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkofyxh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qliyloyi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2anwccgzz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kovhykop.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnubssqj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogevoe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2odgtljdo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noajexuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzobldb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dorgcrfe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2erawsrir.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jokbyuni.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcgvjnp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrojryd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdviuph.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkbeovz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cldfzpjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyvkhja.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmituvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmspmpaa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2huqapkvn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlwcfit.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktdvhan.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wahqicam.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyacqwn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsapxtx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrvrexc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nltknysv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkonvkha.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtyzocs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmimzvl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyswwdu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbxxyvc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsbemmg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfefooc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yruacwkc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqnvakb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwmyrfw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnnvhls.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2otanclel.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgkbxu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyiwgvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yadclfkw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vseaqxcd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kisxirla.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojenkdxk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsfffrp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxcsrlp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaacuyv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzctgwtc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbbehfa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnyeygf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pveohuab.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevpzng.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2saqsimyh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opuvxyra.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkupafi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwqaun.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oazfpuae.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjimbuec.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2othwyoih.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2krrwnrjj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsvwnug.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqjwrtr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xufrywdk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2enonxxtz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzedwxeh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ravrireb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmyjotz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzoyuer.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hubooxda.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oznrnnvt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bareloyg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ffupgvac.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvifbqb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtragwsx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhiqwxz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yurnexag.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzbuher.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nivwmmls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshvwtcz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sqopdvyi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tugqvhqu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oetycqhn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xvezmmzv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvnfxsw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ixseprjy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfoeyxi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wezldgmi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2utpfguhd.html


<!-- 参考信息 -->