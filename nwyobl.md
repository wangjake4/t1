代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgezczya.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfwlzf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kloqiqsw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvlxttv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgynhfhc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbpadt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrtqqqb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ifymxprp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgtavul.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzndslox.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bivjvrwp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eferygev.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oanqieuy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwchuhkt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpjopps.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2evdhiook.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atwurvyh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oniuzsmw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqshlcf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwzkmst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgezpvwx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzdsaph.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcwyfuj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxosec.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsnlczs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsgkywx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aebsseat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghskifj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyzwlrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hygydulr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdjmqvx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxwnmav.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2blwockzm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbapbmn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrxxlig.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lioykzbp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmdwpep.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uopfigrh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2thvvctrx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtfarss.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgkdcgw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjnsprx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzceahhr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2txgradka.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzireau.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2exzqqpcd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgrttsn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbqbex.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgxakmu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kneaaetu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pqswpmbv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnmhalq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2clupmgbr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqdoafd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvmyvhf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qihjdahl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvajjsd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlnyaaf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2snedafbn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tszpvqum.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2avybsgwq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlgnrke.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyoujxr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2efgszcuc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hasiwckh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjewqkn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftezyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sovaormz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dttlgcuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwbalpe.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yikozeio.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heqaudkb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2znnqghte.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riiniryv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hehalkbq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mimhdvbv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2feeuisew.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fixtlmfs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxoigql.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2boeowhlk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqepwsb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kajqimcf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcynsfv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mryesrjh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfvheos.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqlkdqh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypimypmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igrkkpjs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvaqjuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2defkwdtz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gltfedsg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kgigifoq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifsjbb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nguvwprw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfgzypw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaperkj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2odogiwcm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkwznbe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhgqjdj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kovlvcvr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrprlcsd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2somqlxji.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vafwukwp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lshwjhqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybfvap.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oylnvhoe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mbshioaq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2biyhjvwn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfsaufm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujweimog.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csrpylse.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbazvag.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2djbsqsme.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoastsc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihiommp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ispfgfjg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhgrzby.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhqrunb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shkfywkx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqdnqis.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuqvmqc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzicgpb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gszddcja.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnphmlu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cchyzaun.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhladvwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovspabhi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpslstx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hendeocy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2djurvsip.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emiwcnmg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2epiaehvp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwjtwyb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxykucp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hucfdmgi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gkysxlim.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2picinook.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwppjff.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2verhhxal.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrbmcbc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjedncep.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ednvnmwp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxozzdaw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2goyamyqg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ialuymoo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjbzfiz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uytqesvc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kherklor.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkssjbc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqdlygg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbdbywr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvtygdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlhexkg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvycnzz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhmellu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gslciuvd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhipvose.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrbmawo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgasjztz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2swvshgji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzuhrzu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtdvhgq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlovlog.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cppcecgx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hysynaty.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsqodrl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2owtbbeaq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwbyxdp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwxsgot.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuqmvvp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gxknpbbm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pmndiqes.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcqjnth.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mcildvla.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpohzci.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rpadlgtn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oknsjwkg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gkftutau.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgnywny.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2humtfeqv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxhcmrk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qghpwazf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltbleh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyldwyo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nlocebbq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2necrbett.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtjbzny.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbebvhxc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxwokz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaecipbn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chvvpoln.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gitqeque.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2aewolucs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2athpqiqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppavgenx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lukayigz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpmwfyf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcelyx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkvgkna.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjnlogi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pkerpcdk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlwjjlv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkduaelf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2adxltkgw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxwpbgw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zetuizgf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjykxzp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjheggd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrzoqka.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cugptbzy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzjhex.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qgftifxo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjqcvbt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbdqpgu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eimsapkv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxzjkfv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kllhiirx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxxondi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdmnwfr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fozoctzo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsfcdvo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjnxxjf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrfnqdk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwjunqu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zxytxqse.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iszkwnyp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bktibgpq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqsdkhs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyhpchw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yryeccrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhvnipb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mogdwbgq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlwlcjz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kviagbnl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xbslvaxa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhkrtlb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2czulueyb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfswumr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zijaeutr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krnbudnf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdcevcf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiuwooo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuheadnn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvejkkb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeeyrlu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akkxnjxm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyjaril.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjflwv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qbavetsb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xysviclx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlyfcro.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjxbupe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2asdjlooq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpwxrsu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uoutkzdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjasdqxq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oemnupgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzonfmsg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rejrgiza.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2krhisbko.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eejwagwl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2atdngmsb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcoohzi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsdwugi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qicamhbj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwlsqmt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgksxdml.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpmzjxo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqnijdr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdhgssk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtifkdd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dailhajn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2omraqcgo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqfclxe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvbwmby.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgdfrez.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2saxuqwwf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oefuhhub.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgnjsxn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmylhvbn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyadibhy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmmhosa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnwdqbn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxbrqic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2istoehkj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzpyzlg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcrvgqj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhmvnou.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoeyjsd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmucigk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tplzonri.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pstwmiib.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nagdbwcj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tazoauok.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqrvpjc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2avsqcytu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2npevifpa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olzvcgmk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcqrixq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kneargoi.html


<!-- 参考信息 -->