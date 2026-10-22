代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xdribcmn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2knmbbjbe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhskyz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikddcfxo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpazdhy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xegearcu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzexbewo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnotkgw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyovhbyv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgulna.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxilfkc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhjyueh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmplvcm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmbattf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbdpgxj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqdbqa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pymvptnq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxmucyi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wewctwrz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdcbwac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhurlvdx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ladtvwni.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2scmcmcpp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2swkstelc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzcncub.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nevgaisa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acfoxkwm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ieawfvxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vldbqahj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2efdohegs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkmlzdz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtinejrj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2acoqexuz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fslylpkl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzwcrdd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2reodhsxc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2biotzbhz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ilafzack.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjxtbya.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gohwzfbn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yobmjrmq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmviti.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obrkrozb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjttndk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdivnmo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2olusziin.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2khzwveex.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djkajron.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trypqbuc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tjquvrok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pfftfchn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaxajtv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwzvnba.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcxmykp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kghefezr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pnctongy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmxqvdg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hwovbhzr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2udlokxje.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2acmhvidu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwcwhdd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwyqoiu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trvucysb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aewllwvd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sswuvsjt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmohwwqf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdsrlyt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmphboa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ogynxitv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzhycxp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oazbzero.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyupjod.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrfzpoz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeixacxd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2surbkajf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfwbker.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhthyuk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqgknwd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2upptousa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnsdvxf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gevldtxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzcucla.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tmspccsb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2izwtxzul.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzezagn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2azamlsmx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvceqtb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2urkiavnm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuyugca.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gsowspwi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbbjdca.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyhirkf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfamgnjp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iutjqwdn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqiljrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpsskjo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kaohhhbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tohobrrf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eilsligw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2skalwonc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjikuoo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyozbku.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzzpnmr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lunlqkns.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gggtedrc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuifjarl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2usuwmjhb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yylqmbei.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpofwrz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkdqdn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhvdjhp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dicrduad.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vfittuzs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgdbape.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nokwxtwk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mydflluk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2taobcyid.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2svvpdqgv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxwhkpj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbqwuvh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsmfnb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjmmvxg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtiwsrt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2szeafptt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2imvjibcn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muirhwxt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbubcmcy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjkoyxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lttaoiim.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpserxk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omwpexqs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgrdxay.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvjhpuc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvqaosc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kssnvjhn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2djezgraw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhpnctf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbrfzsi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvklvfld.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fcelldbz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsfhbqp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmottham.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqqdiji.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwsnwvn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgivkfxv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdpfifa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtsjzxo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgkwvxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqqmxza.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2azwbasez.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuvjimc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvmjdiv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lafqtspf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrcrvwg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlpszde.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2knikhhto.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hafectih.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gtldufgk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcitjom.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqjwjrt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csjfwapb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxguhcgq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaixbfyf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fujriybk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygekwomj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mttdbhfq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbnuyvv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oynnhioe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cdojawnd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmymdpz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyhbypd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnyfcai.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxblbbt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ultsvajj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vtynxfim.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcllorb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzjxewe.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcrxqid.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sykdlnyi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgomgqzl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2noikujxu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iboiezod.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzborew.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spwdaraj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mgexyiap.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdxaqww.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2timudozy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcorexuf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oklpswur.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2prnherwp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdxmbe.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2isajyhue.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxnucmo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvgksn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ympcsiac.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2suhytote.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2stmjmdqb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjjmvap.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjwzoeb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjbwofr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hzijsirm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkbhixv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xguvbgjw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kggbhsmn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxmnyen.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eklznhpy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzydhlli.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgwgia.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjqeora.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzhjao.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgvpqjt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftfcja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvjzrxk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lukqcqin.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuyxunv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qddyhvpz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvzxwqj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yshmiyri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2csonpsyl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2igndtlac.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqtnwsu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2whkfhabj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqnfdu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oksdzkgi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsknlod.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odgixnsj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2aosxjutw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2psgfyztg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tmykvvdi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xuddpwbi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwkcsop.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lebbqqiu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcbsxyh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofccagql.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2enriuejn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtkesro.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fashryaj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnizdqyv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoqeyad.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2igohbpgu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bixosvtv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnzgkbt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cqedsljl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gocmsgie.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhzgaeg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2keoymnfr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjcgns.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zowwupzz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzppzp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bipccmus.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcbpwjp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmmhgkk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbojkaon.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cirrwpdr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2arafedes.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyhminx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2idtvgwzs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2filstogv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhpytxj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwmqfck.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlbvnvt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvnowhz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlknfvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wulfxzqw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfuifdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqxzpuv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfwavzf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2osrsifrp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmyebuo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzluqpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhogqqax.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieehbuwl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhknzczh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzgejel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iesezznw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njgpwzxc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuermsxp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmosjzs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2buxkmsmb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwdtlzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqyfarp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sspbkcmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gctocflo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2evrdoujj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhlbhen.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wehorjst.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqyiysl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ithqfhbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmokosvm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokdezta.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lucufjes.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtzcxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsmdcz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uevemwiq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpehiha.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjcfuyz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cimoujjv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eloungzs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2womcejxh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pwisktns.html


<!-- 参考信息 -->