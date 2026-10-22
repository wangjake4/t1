代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxxvfua.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvltnvyu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2csyywmot.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2npwfbaby.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cjobgabi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxjzml.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bytthhoc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfovwpvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrqgtef.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyqijzp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehujwvdk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgronxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teuslyhy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2evxtmeaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zngesiat.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iysbuchf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wewfwovr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gtktcwpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuqlmiv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfstmwv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvpwook.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlhnduv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbaixkn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyceksx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hufbyfrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iipbmnoc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfekivf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2woazrpum.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2abufcqjz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaapvgj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jezltwlh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkskhqj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbegggb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zotzsksp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmplxdp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjfvonu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrtcrns.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaamjah.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwucveqs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zodtdvpn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erkulsqe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2obbvhdlu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmudtzer.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qoobhtiq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odqlgyhj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kmutyqcb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzymrapa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2liftuifk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqgqjq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhazpthi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdxcyii.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsuinhc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvmrvhv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyjgasx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2twwqwwvd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcapouy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eoovnhwu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nclhyvdc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbffrhvq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2eawtydfj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2htxmneik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmqpkpk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skbftacq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuenvqoa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjrbdyv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhqxpwz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkusmehf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnrxtcv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvriruo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbczibap.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zucoslia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2exsprdho.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxlsicy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2esyturpy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iddqbfpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxhlnsn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjjvgmy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbvckkc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrykcxq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbebyuo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsylube.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbjvxgj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbpcvzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btwvqnms.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pyovqhxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbyfljs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqouvl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcjvspw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nseirujg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpdzmuq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofikytpl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcopzmfd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2scugmnoj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aimbwiwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqpjqec.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kexbwtny.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyerfbf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2udoiclel.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxreprmd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtqugtj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2guwfpwwy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqpdddv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmimsil.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcbvoed.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lbduqfyo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmsyuif.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgplywt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qrefbnvp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oollmdud.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wezybnmv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrulxbq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgqtlao.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjdiwcd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayucopip.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oictkgnu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxojyhv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syhmzhvr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hvurdpzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfohrzc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkafyps.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqgsdyh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqedniz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxblrbps.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2agtmeugq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2heoxugoa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ojatigrv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwaldop.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyfiyax.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzozbhfn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqezourf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtdijtj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahxjlh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhdmahb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vunzmheq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvtgaoy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkljiyhn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqagdzze.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvzgmod.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiojbpoo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzpaxsy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cklmpnvv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrfetdl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmnpkvr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2luatuvgd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zktgkoxk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjnjxxh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgyydmk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zopitnsm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtrlrzs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhegmvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dapsbcde.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpmwask.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgqbbdz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bduxescv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2midpkeaj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfirogs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bzniggue.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vghgbaon.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eucvboxv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fdndtplp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdztgsvc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2thdtctcj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bippbmys.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yproidka.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rarvxgcd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvvrql.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eggbvtha.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpatwba.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bijubanl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqbphmg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vczduogy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nebtrufl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gattashj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cijwxjng.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2upragcxd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xabncylx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhgmum.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gabmxgzp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcazzen.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fmghghss.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyunbxp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqyygmc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtqbssq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwbemwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbmelcx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxorxvcy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onxijdik.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrtsrek.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjdrcf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2luzqphfk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbxdixk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqqaohx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2emxaedgv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fygpesoo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcupzker.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2emsvqhlh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnwyuun.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zogtnkcy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvujxpdv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jenurtab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2npnzoslu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdfdrkv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tarmunlz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2afnmznzm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xicryjdz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsejwmuk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrmqvif.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tunaypna.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2igpkfdsf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsnqxnd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoyukrw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dixitlnp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wurpwuxx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuonlpa.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2flhcrhff.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2igcpglts.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtgqhmr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwtunr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkztcua.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gaigrqwi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwrltl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqixwcvz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2peoacwrx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucohwyfr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhqgfbs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhtjapf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2peptofvh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2byiplmak.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vouqktuc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pkizmzfi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nquhqkke.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldowvqxt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2onucvgtk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqajpej.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoolhsz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkvuwzs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2emevkkfk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2glufbuhk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqbroqr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otgapfvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsukyam.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erkfbwrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rvktgstv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2faabtjer.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wiajemgu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tdntulbs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2avawboit.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvsfbhw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsxdzkk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tmutxuyh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pkazlgod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yamypfhy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkxvsty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnjsagr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdvtvck.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvmtwhu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgpfef.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2surqgren.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjylgjh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfmyvub.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpfnfyh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhuyjui.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2inycwaxu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiwlmdi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnareumf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzcsfyf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xoujenai.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqbjirm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vytnusfg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zjggljya.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifurktar.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdiykzb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsgpcu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfuqbov.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujvypok.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqhifdn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvanpxi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2izprvqqc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cplbxscx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyngwum.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2evrrzgdu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbhmgin.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtudgtj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fmesfbfn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdypkgho.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkzsjjy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbdxfgh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnrsaon.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oajlguyr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvmsota.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztplseq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oipepoby.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifppqwz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpytqecg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpngvvii.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pgebprxq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znewevec.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkfhlai.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjwkuxa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoxrytc.html


<!-- 参考信息 -->