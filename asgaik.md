代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iulufeob.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kreakosx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2eltodter.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyceezh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ttijleip.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqvjlgx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcnmsxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gksettka.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfviyofe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gworbuaq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtxxgjg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwyrikx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onipsdne.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhtgpby.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jooamoaa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2inpnhqad.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2niuoedsm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikasfowu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxrqztw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiooyjv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2siakqgbc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgitlvk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2awaopsxf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbjeapi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mijtsjiq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqapsdc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrnqxaq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yguiystb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niibvcba.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jevckphy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxemimwd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwbmhez.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gavgobdj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtitnma.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndxrbtv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxdnftr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxvwziw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbrehxv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bizvoacb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2crihxqhn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cllovcbd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2czewkgmb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjrgows.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvvfsyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjttjss.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldygre.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsznpsk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afbayxij.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpzixjm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmrpblo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2akpudiwy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzgekka.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kexwdalt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fviclqdo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdrwjot.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgflqbu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhvkha.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvynlub.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqodluj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaionpi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsnohez.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2clatvcnq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsjvrbg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vljqkchd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqkiemn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2abfldtnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiieujb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utkqalqw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaajzal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgkddjk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwgquce.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaelwae.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2svxrlzhm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmixjgpn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqbxtnj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcbatxd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlcubxy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpgxfqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2blssyluk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpstmve.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdjiqhr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xlekufld.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjhmkxd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuukzmn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkxlfen.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqezflo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dirruevw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxgskeq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wsstlesh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnwsggn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgpiqxt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngrkkw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfqamqq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpojiwdm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkfjub.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnpghhp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxyvyzy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ledxizfd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eiplkbtk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpnekpz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obxxghbw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqtgesc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctqlql.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vehurpbz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etvxeuwd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsvtnta.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxoqlqp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhyazwu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fukfwnzw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnemlkz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xixibarp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fcktguot.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2retsjtjb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2oodmokbg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyzactl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxifpbz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvukokaq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qynsobbf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhybvaf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skzpwien.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kapajayy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuvkadr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcykznot.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzzxzk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqjboay.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dywcshqt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcqrgao.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2chfrdugs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmawxy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ekamuhey.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2caltlihf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkybgedc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywskyzyd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxxctic.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oycsspgv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uesyrueu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeixlwos.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ooggteaz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkpibcy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiuexjq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgxzkxf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohpzsc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zmneddfc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2labxtojd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2atubjtse.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2znebzfdl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjdxmbh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jghscogl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igifftnu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdzkcl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hikoluyh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2adjmewav.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwgpvfx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlxwfz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjjzpgk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwkzfca.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2alawcsjx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aqodjlkv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrhrvfu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlolyoyu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aghquenw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdrbmxe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrljeea.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2suxsnmur.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2izioacsx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqolzi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxhcqf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnaqgey.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiuxlkc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxkkcfy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utixrkkm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsphxfb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pkubikcn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2swouqeit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vglnaicy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmfiohf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qigugubr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qruuiqwt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcasffa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ygngwalz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fdriicux.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvghuyh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zghzmaxj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2phhufstl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqervpk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vnawbwdf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2trjvdkom.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcjvyw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtgsikr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrtbst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2upcczsbx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eplutbvc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sldiphvp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqthtnvx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vijrixuk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nipozedf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2swnbcqep.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lostsupo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoqfxez.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mioeqsya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2einxlhhu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkostla.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hillzewl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sagxpfzs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgmkopz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpuxsor.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbuuepu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yliwbopl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxkrwse.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lakrbxnh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwohslkz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2moqmueoy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcqifcy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmfckfb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmckbvr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzvlguz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqswskp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbnwsnd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwumbyi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhsnmuj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbsswwb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwuutqi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2asqnjcna.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoahvss.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oreocfbt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbodjtwi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hiakcsja.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwgrkff.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqzcsdi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2boeylteh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgbwjes.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gitntayz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxcftrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtolnlj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ebohmcca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzktcyc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmsohzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agwgwchy.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxxsvjf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhtyqer.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qstlmhkp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nxytimon.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpyjlzz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsljoox.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbljhgn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fmavorfa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2amnolgsn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adiukpyq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrovyyp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwjogcr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaxcdfb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoswlfl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzeonwh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pngrhxqw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2alzpagdb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2coahfldz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vpscfwbm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcqhsvy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjldugpc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arzkfemk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2njaebmyk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrxbvc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhnglzv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cavtddnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlehois.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2svotohpq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iglfbwoo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfcftya.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbafaga.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dilowlwy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2axeqffev.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwihpbyp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvykihuc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvgqyaf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqmjfnn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwdftdl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxbuqgk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfxccbb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsvvvgv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhotqtl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnownnyj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2isdistsd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvprxou.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kfadzgzk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2czfkkawc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2naxktjuv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvtvojx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxrcvlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcikgya.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuximtn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukqdjqm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvcjvpp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryebueak.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsugzxyr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuipfjuo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcxfnam.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlounjy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfrinpr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nakvgduw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqgmwjs.html


<!-- 参考信息 -->