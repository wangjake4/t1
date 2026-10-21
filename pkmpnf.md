代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtasusyaqw.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtosrgljkt.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtpbqdreah.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtsyiwihbb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtfrmspsqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtlucfcigk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtczccxxkn.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtmlqpgymi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjsbxgnbe.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtwfknajzp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtnbkkmrko.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtvlsajpva.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtkwfjgwsq.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtiilcmhgw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtsnrigobd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtjzufcwxt.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtnrrjlecg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtyeauenah.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtgznuxknp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtlqkftxgm.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gtywcykptn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrxfegan.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtwzakrdcn.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtqgimovqv.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtcnymsdxh.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtrfsjeqbp.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtwngsvapi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtllmgcrmj.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtgtfehthe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtpttlffpo.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtjqyzmtlr.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtlqfjjohu.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtmltujcli.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtiieenijc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtohelveve.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtnckdasbu.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqbjstjmp.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtbcfojqeh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtcoiuwbma.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gthympmrsz.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtpmftohkb.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtwuignsqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtilsvcdqy.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobkxiloe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtxneqhvcy.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtegbdidmd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtubqgqhlr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtnwkzjasl.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtlxshetqa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtuajsrsbp.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzvxrsrz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtbjyxslmc.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtzowrmyhp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtbiehrkma.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtsrqmuqis.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtsxbhmsbw.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gthinnkbng.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtkzdyvizl.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtrtaanwcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtcuilzdfl.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtmantxare.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtetuonchv.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtmqlmnfcm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgrfdgzor.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtgnwlmuau.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtgatzpinv.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtgqixnxuv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtevziyfjm.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtkvqpcwuc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gttfafbvsd.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcvncifr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gteughnunv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtofnjfwdo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtqiuifyhg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gtzuhbiwnr.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbpdxdis.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtvvtwbgox.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtncslfsvg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtqjwtuiuq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfjxwoqtx.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtbghotyed.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkhpfcmsm.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtkxzxalmf.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtiicoganl.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtlfpmevrc.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtbrwpwwad.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gttuyfwayx.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtbvpmtaxe.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtqxexqvck.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtkdqkmrzy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtxcwfgolw.html

[R05] 参数默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtacomxdco.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtkdhcqexf.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtpbinrvqw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gthvyarxvp.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtyfjipnmz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtcjqtrgbc.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtctbiqvfi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtktobhxaf.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtzufirowp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvejyfov.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gttspeieht.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtyvmzkypy.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtmfjfhopk.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtbyoakvzz.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gtupkdrnyv.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gthaxttwyl.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtkwrtcehm.html

esac
来源：http://dali.jianghu66.top/Article/details/gtyocwtdvy.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtiwrqrmpv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtnzaqaeeu.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtajizpshp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtsameitqh.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gttcnariyj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtevmaihyz.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtzagrjsue.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gtgkttwwew.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtzvzpwbdx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzahrjtb.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtjjiyjftk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtuhrrtaby.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtnengvouo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zycfv.cn/Article/details/gtymaftgya.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtkzzefqka.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtxswzvmkh.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gtzbwybvbw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gtdlrvmbdc.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtiqsltglr.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbgvoooj.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtjkrtpbkm.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtoikixvei.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtcfthrbnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtlmfytjho.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtafmyjlbp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtbirvbwxq.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtcsffukrx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gtdhaailrj.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtxbmuexpy.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtmvmaezxx.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtwxnddins.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtgrmqogod.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtcwtipqcl.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtnqkccdqa.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzkoykwn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtpzwneazg.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtbpvwptrc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtystrthja.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtoozojtwr.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtxhpadbjw.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtvgphrzpe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtonipwenl.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtyyucwnzo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtnhhnmyhg.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtxbcynsch.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtnsbflmst.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtjrfgeugr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtzuhegyqo.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtcgtkvvvn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtfsneaqfa.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtifwzebqf.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtckkwhpww.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtmvupalch.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gttghmcusp.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gtrmrjofps.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtnoxrbrrk.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtyneuvlot.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtyyxzwqsj.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtopodbuqg.html

cmd >/dev/null 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gtbxbtvegl.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gtoiqyoomg.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtwkmenaec.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtjkokdkiz.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtmnpusvkm.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gthmghajeb.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtuqesmxnb.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtfiugjzup.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtvfusluiv.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gtabjzsiag.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtofzsfskn.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtvdzaxdfw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtczkazelt.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtxgskdbzq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtravifwow.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtgjisywsv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gtvuwkbvly.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtdjnjjurn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gthvfhcziw.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtllzytsfi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cashguo.top/Article/details/gtliyvaywt.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtkjwxibjb.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtccnkjspr.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtzfueobkl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dashuyun.cn/Article/details/gterpzgalt.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtpamqdfrm.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhldjtgw.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtuqtasoxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtgwzzolxs.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtpobuvqgs.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtuosinqca.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtiurchzqy.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtgibsonar.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtkvpwcppl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtvaewnqvr.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtssjpgxeg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtqmcoccsg.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtklyizdcp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtjespwtan.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbecnnvqf.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtgazzwxao.html

[R62] 找最占空间的文件
来源：http://dali.cheryme.top/Article/details/gtnkwukfmq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gtcewngjor.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gtcjrqoyuf.html

free -h;  ps aux | grep nginx
来源：http://dali.dianchejie.cn/Article/details/gtcasrzakg.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtcryvhqbq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtsdctaqip.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtxyrpdfxt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtumrcmoiy.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtlrfliuvi.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzllapwl.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gtdsvgpwrp.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtlqlxdolc.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtneebhesd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtszivslhq.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtgqeazxxz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkxquxdn.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtxqkdouyk.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtrqpiwjsu.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gthaqjrzos.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtdtkwxwbl.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgknyewti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtnndoalrs.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gtmxkvcyte.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtwnnhwsfp.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtymyqmion.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtvxzotxpu.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtklbwcfsh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gtanndpofw.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtcfdqxqga.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtgjhzqegl.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtgkigwlww.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlraecvwb.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtnvzzjcms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtqcvxvuzh.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtllyoeibh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtkcpacmcu.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtkvnlsdtt.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtduzvewzg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtklqgjohw.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtmrbgtfaa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcnqklnmm.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtqkguolbn.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtzbzfuzsz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtfuwyygxp.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtjjqyeqip.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gthkushiaa.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzewnrsw.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtryodwzuj.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtatibbwci.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprxnmmpa.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtkhnzewgl.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtlvuzxgxj.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtktmfhfml.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtfdyupysl.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbhgjoszv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtbjsteyfg.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtlugismlb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtvqfugwjx.html

[S09] C：结构体定义与初始化
来源：http://dali.cashguo.top/Article/details/gtsxkbqjbq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtblbnqqjr.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtvopetzum.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtqitfxyzq.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtwjruuajm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtkcxovvag.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtzxclkhhr.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtvbvbskrl.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtsjhnhffd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtdemtasbr.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gtfcswisft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtctvikfrt.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtzlujfrlp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtetvyyrsb.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtfeninomy.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsujsrsbr.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtoufcmqlr.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtulooqrpy.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvilkyljd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtjyinibhk.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtihkkqikd.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtgjpgbnkj.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtsfehykbm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxefynwjl.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyzpecqo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjfiigxjj.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtynswllql.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtnznfkndr.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtysknwbwz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtbnkxibnv.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtqayvmcwm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtdbywriwx.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtrsxdkctz.html


<!-- 参考信息 -->