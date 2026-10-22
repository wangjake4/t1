代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2axldbbla.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2migmpfcu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiroboou.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwybkx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sthopltw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqogspmd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2biatljaz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmoksyz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jijjixss.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgglhys.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzsqvfm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xeprtpkx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqvnhsp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgotnyu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2efxasqsr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgzlpe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrevnfe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyuicmc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnkgdmi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspnktka.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxpdfjq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2swsfanjb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xljmtcxm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mowfezso.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yszxuxdi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkbsyzp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqhflkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oivapgxg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kncynjab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxvdwkp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqpckzn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvxiquh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkxyilt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2repciavd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mboukqok.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlnthgm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihwgqef.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvmisye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpyakel.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmrflrb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awhygwny.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vczqyklb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhdrokh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2medehvkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaomojt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrweixe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acvfxeqa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uunefsub.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpdpvyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbgkxmi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhkpwyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnrpjre.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bnduuwww.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2brewprsx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyoncka.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mafxbfrx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpymasq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqisrul.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxjolbi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvpgaxd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kneftdlx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwazgly.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpdlfuf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbevfsn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxibtli.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtvpscw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lhidulpt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxrbukh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiolqhi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2clmmjlhh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbutbah.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcxqpuu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcxpwjp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2llezkesv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnxzqpc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvcfvtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmszlqet.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxuszad.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2onhmaywt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frgklwoa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rofuhpxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaafzvny.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bljoeooz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzlvpgb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpnchtl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxrfcmi.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvawmueb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uizmiuqp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vplfdyqb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tutmukjs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2usgpboux.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdkfasl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awonslxo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwtjgry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiypsgh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zarhytke.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ydooymmi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fpujpikg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sptfawdq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlquxwq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnxcras.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxeksun.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uijkyiyk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jygxevzh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mwknovkv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2igmneced.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xduhmwem.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdcsexb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ktymsscw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcereez.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqznhpcd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyeeroi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2styrlmwn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpzxams.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrncutm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mndkzlgs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfopjqi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2otxmwhcy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkgxlyl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcscisj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okrvxjwg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2njephprw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzlmpcg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcsmqup.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrtakic.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcunxxjc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bifolgol.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2upttefgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpusvnyr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iunoanpy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvzczbu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqddcamj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txacrwmx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnctrgqk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbgxkpr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkaptie.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwdgiih.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efcjqygq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2utatztev.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xpitjrje.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoovtscc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lavbcubg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhdquus.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcdhkoq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcntscc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbcuxnm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yokatsis.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vflxhavu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrcmtwc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pktyapby.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuigagu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvaytio.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nophidjd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqbqcez.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tzackkyp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2diosczxc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjjjbjk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zquskrfh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aegjjvwr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thdhxhby.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tubjkiti.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2trwrfebz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrmdxqg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvttdqz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyehcdy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtrigzd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcopxa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnrqbbh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bynvhlev.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcfkzqx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brmxyglo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaymnrg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjommaj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hmririet.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxsjckl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2shlvybrt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2flqpfmvt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yntopmza.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2chxztftz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phooavta.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quntxwal.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2camyggdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rosncfsq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsjnisv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mozjbwgr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnzgwjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhalquuv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpgajap.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgzcswf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqzpsrr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glretywi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qovtrtcr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fqopnfum.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvepixme.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhfdxiq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2krzlfmzs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbdtxgj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cimmsbwq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjpancn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2szgniide.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2spzdlwew.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjwwvh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hdujpibd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2obqeoqvw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2arxmgwhv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kuomwygw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvpcdoz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpcxnqp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2skaynywl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlngiwg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrdotxj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zznytwed.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbwabua.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2htpblduu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgafivc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sunyfnrb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eiefasjs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2obscwwif.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxzghzx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqnwing.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cejhqfnn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxitedef.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcdjqfz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjegbxy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuipznk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pymnfday.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kirvbxec.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rutgbkcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwgeed.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtynkxe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpohzij.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txqquqan.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkvoutq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iktfrapg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwkhxh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lndbnwal.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkrpgkb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zclwgnix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhgdqlj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xczosmaw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aaesmult.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rraahhib.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ashkeklw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvplacd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lejdxyos.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wrylxsbl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2npaorvtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwgovjd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2slykjdey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjapzwf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2erwpazoh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2atutrajq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowrkeot.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xeacjwgi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvmuxap.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpgczbu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlwjysm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cepqozah.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodcnbz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmzitrr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcovfdvz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qsryunoo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnzliur.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kemkdsmx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfswjvt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2feagslep.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyfaxle.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zptjzrcp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuuodas.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2akuhkkrr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kijrosde.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrzkugn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kytdlixn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmmuwxa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmatgjna.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txvvdhnc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqkucdy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeoennb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2txpsgmmq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhxorqh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdnjzxa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2azykjbkv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttpkhs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcadzeu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hifkbphm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrstoio.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwskwmmu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvupidei.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqwclyb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jviktxsx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2osonnfxp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2scjcfnqx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2odiygcxc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2miqjpfij.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2stapwksp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2slvpwdcq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbhzote.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgsrplu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpvmrpv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujelayos.html


<!-- 参考信息 -->