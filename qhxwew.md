代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkslfxng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzovsszm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgagoq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qghrbuhp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rctiyjhl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uwszrpjc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zywfwcev.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxqbugd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yysxpcyx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwszxhzr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2womatvjo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwacbtt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuzhibu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhfgueg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2owjkundl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgnivtx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxousow.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2izstpabv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rebvqrlj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyqarqq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtvdhmg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznsgglx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cldvglgo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbrutk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrrnfxo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpcymju.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfqolhb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuulqupb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieomegrp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yavmnitz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nudazmbd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uioxrouc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdgbevy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lfznqqsp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkwiutx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqobwfos.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btskeanc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrseejh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnlykyy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaeyjoh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkilsspf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbsxvph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmyonph.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zepwzbgx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aqccavxi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqbjcc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hmejxwoj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqmzwue.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zczpouux.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2coyibugq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbffmpdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnqgrhr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2glpbpmvi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hovpvlqd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pybwbogl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvouhfeo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrfdplh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zclzyght.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2indnkxof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgivnqmd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsizzwl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpxfmhd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzcnzqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2efqctkvr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpxrras.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fmusnnlv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxsqgrw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rziiawrz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2utjeauxr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsjlfrb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhbpajs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2phynliwn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2avqtucul.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrsxmoh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtlktm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvacflcp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkaqoby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aibkkvya.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrzhbxv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eobvkfsi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zthhrdbz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyceyyz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnztmol.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfbvoxa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rplgtrdh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqmvacz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwookbaw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iadcylri.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeuvalj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuionlf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuajgrap.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upsnfozk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qahndthy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lzltfovp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oawsszhc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpbderu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zqntxcod.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuubtwa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mcythlxo.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jzudwfsa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmaufgq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gowloptf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyqrvbq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuliwzvd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2idemimny.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfosfye.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkscod.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pajzsisr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjqfgbo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vapvneue.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiosnsb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oheqbzrp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdgkcea.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txnqbies.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yafbehkm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2odnwkqor.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyqznjn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwskoaz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfztshuq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdwwfbg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igsehyqb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmfppiy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkopfuth.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwannh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcuhslf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlteuef.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybsatn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovycgf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jziosbre.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmlgqwl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhffone.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ondzfrse.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfgenng.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmieylhk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnufrfxg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bgupzxta.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdgpyu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jtirfbjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfjdzuj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlqwpmx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxughpc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcwqsrn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmqhgx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkutoen.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbvtoyn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qttvmson.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbzswtf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnnghnu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2abdymoce.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcnrub.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqkyxdw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnouvbd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcnkqri.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtyquvd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzylgkt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewieujre.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxtrcn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrczkqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2frnfieti.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mushbyov.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2izqkbjjd.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjtsmlg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sehlmbhh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wypotsix.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2goldpnkk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnhblct.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bszkfelr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrikjtm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2irrfpxrx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcogxiz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jwonkbpi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnmaef.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnusmbv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2goekvmcv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqskxym.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdigjxut.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztxxrk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlnlyox.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuoeavi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvjvdn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvhvok.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nsytynip.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inlktjcj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uuruxqyz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjspjhh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrgkapc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkswgjz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2csaxvxlh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2psspswbi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cheecqck.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rinhyszd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iocqnngm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhgmlzb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2klkmlpaa.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nflolnzl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hezgoxdl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpuboef.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blcalfpf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqjbde.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwokznp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oudbcdim.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jslmvsnp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvpmelj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxbszo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vymqvgma.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwmeiyk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2frtpjkid.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpgclia.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdsitso.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qokbfvbw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxgvham.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvytxao.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aojlhtrk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dydjuhiu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqlczjf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jamxmibn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nhusmzul.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2reedtslm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjozisg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qaburhyv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxosvww.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2afojtwqh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtcphsa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcrevzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrejkrx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjpvess.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyfdvtu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iouhfqik.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xexxejzv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2afaopubj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwvriut.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2texfifuo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lerfxzdf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbdygfn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpwmgvm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzvlbeb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ochwsqhu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2easizkii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evfxthdv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpmohib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmrobsv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvpsdsp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrlqvku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtbkzzb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zwglcrxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plwrqaei.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mywbzxdm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2abqgxswc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxghtan.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhxpyrm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajjoecm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbstcdn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2drbjydap.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsubqfi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwonubm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ugruiumi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbhuxam.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dieehylw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2buskkyvx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyxhyih.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnznbiz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2evdguwiv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlevens.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmzfwgc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vszwezgf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2psnmztka.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrkfdm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jujwvxdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgddbnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psflqzhx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnejhbzc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpalkfsq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyfmrxc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsytvd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhbpdjm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qiczhdjo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvqthzd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2opxcovhb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hecidawi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cafdhcgt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gubdkojh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nukgzksp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqkbfmj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpykxhh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjdrlpp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxglyqsm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpevebnj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2abxafkwj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2obnzruhd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xycfukzm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pixgtchf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vdklxrpr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmsgjcg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2czduilva.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpluidc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdjjoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2luqmqomy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2osbavrdt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlmmveq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpgslrp.html


<!-- 参考信息 -->