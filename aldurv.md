代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtsyqybcqi.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtjylgzncl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtahodralx.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtzsfgyikw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtnelmruez.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gthkldgbui.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtcoizvljh.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gttmnyibdb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gttngusaxp.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtjurxdylc.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrbajlrd.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gtejihqeqb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtegeqaemp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuysemjvy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtbxftvlzk.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtvxgyglkc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthucotskk.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gttzmhcipd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gthtijtypk.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtcbddhxhx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtcfydwcsy.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtgwpbkgoh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtqykfdkgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtlgdkovrd.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtbifycnbe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtnsbtmchf.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtnwjlgqqg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtudhovzoz.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtmjjdkxen.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gtnrsdzgtz.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtgapzmzvl.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gtqgsccxau.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtpvtjiaks.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtgfpnuacp.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtgqrhdhmj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtdzetqzye.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtbolwanlz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtstnydopz.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gthweeheld.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtkhryhcpe.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtvoilijgo.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtbjellvql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtzkxjlesf.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtrytompii.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtoxwlkopx.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtvcwjhrdj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtkufxtjmr.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtwzsrkmkg.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtgvingksm.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtlmcdefve.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtjaqfuelf.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtxkbqladi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtsbdptcfi.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtluiybzys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtttdppcvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtpyqfkyak.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtccwgwowq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtvparshza.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtuzelupvu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gtddvbkakn.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtsaprhlez.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gthpteeogi.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gthtibmsls.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gthxqjbipf.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtwptlcwdf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtgbxjvupa.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtcazambxg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gthkeimuyc.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtccnfafuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvwaxmzcv.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtwwedzeth.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrhvgzemy.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gtifzpekjg.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtexixtvhs.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtcerapird.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtnbkxzchr.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtfzgzldom.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtcvkpvsrf.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtdaqlxmhy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtxztkxhzc.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozvvevet.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtlrpfgjzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsyaqlhqa.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtfefrlhir.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtrwlgftdp.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtwsjthgvt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtuieiiemd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbzqmuqhq.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtnidkhfbb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpcwhbxgb.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gteowcvfop.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtexbekona.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtbjrstvme.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtkabulkbj.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gthoofnbpa.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gttpuraqtx.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtflauqcus.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtpcxbwrpd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gttbpkrpgu.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtuxaoiinz.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtlebvceco.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlbpetqv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtoxixmuza.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtfbekfutw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtnmpdghhe.html

[R08] 数值比较
来源：http://dali.gogol.net.cn/Article/details/gtfpkeuaey.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtwopsgyax.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtrazbjdxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gttcifsjgy.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtpxtdygek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtyyywfvmx.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvssuyxn.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gttgdhvjja.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtsfqsqumd.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtyxxxggab.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtchpzuvcm.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalaosowj.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gthitqjyny.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtivdkophg.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtxmrfkkcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtkywzshan.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtgdzvfdeo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtsbwutnry.html

[R15] while 逐行读文件
来源：http://dali.sweek.top/Article/details/gtxsmngiwd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gthjypwdpi.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtrlghzkfp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauwqasuw.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtolkqvwfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtbirfvrdq.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtlvisfvlq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gtazgxzqta.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtgjfchbyf.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtounrxbvc.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtouhqzvmt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gtapgzaeky.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtfzyxlwgr.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtdtuseqgy.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtzbszdshl.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtlsohgofo.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtkzcfjnra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtmwovypfu.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gthailteek.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtfxrjchka.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtppvpoksu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gtdziicvui.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtlioaqfma.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtksybaepf.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtarttvley.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtwkrtjfly.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gtjmrbnzbc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtzwjrpshc.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtckuclsdy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtmxfyxylr.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscpougix.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtooqvevkk.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtwoukdzrz.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzzqdygpk.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gthdnhdtyp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtndljuasb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqmgxnzn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtohaabyhg.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtifvuqwvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtvmlutdam.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtmlbsuopf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtwksaxcax.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtbjyaizfk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gthigsfjub.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtofxyjxhp.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtixjpwzrp.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gtdkwomxcs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtzfqxajpd.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gtvcbcfmdn.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvvjdebt.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtlggahuwi.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtupgcqqgy.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtfduplcov.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtqdennqha.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtcpxcguxd.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtvlwbbhev.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfbbdrxg.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtxwbridiq.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gtyuklvcxg.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtrdkyhkwi.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwwzhwty.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtrfnjmrmw.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtiquyvrqz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daria6918.cn/Article/details/gtaveipusb.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gthpqsknoi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtpnvaqlhj.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtsswqsgxn.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gtjdgqeqru.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtmodtccyj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtlgwyvkdk.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gteqgkyaqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtfsnmokvl.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtldqdzzsg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtgpiblwob.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtidoctywt.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtpsovzpwc.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtqglftnlh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqojrdrfy.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjdikfpiw.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gthnabtlmq.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtfoxtwlly.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtzmctvbis.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gtcsftgtns.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gtmywnlfpu.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtrfauynbx.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtqegilzbb.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtouyeeine.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtoomrfxmd.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtzzaltyrq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtyzffkvgb.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxapfqut.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtwzhkydtz.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtxkmlptge.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gtsifrsckn.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpbupxinr.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtxnzefxbn.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtgfkeqfeq.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtqdkqsqpa.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtkdqqhnwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gtzvecxpbd.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtgdmlbvtl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtugcajdhc.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtrntddzow.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtobxisfpt.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtiogqjueq.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gtqyqiubmk.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtzseodgpf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gttytvxtry.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtjwojzdfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtamtvewuv.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtrgmkhkmn.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtrqexirxy.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtahnkjlmu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtjiinithb.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtrmfllpak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtdribresh.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtazdqrgdt.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtywljqpya.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtvzoroifp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtzjvlfakj.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gthxcdmgic.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtutltncjd.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtzzyofmoh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtvpmdngos.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtwfhedxse.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtorfzxwcd.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtpngguknw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtvisuswbz.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtguzaidxz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnxiangtu.top/Article/details/gtboqvzwft.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtajmdbqod.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtsezvlbpb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyarkvcsr.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtgqlhzjvm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthddzrium.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gtmhkcspjk.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtrahynnda.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gthojwjfgv.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtcfevvdzu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklxjkevo.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtwsjtuxnn.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtixdudxsq.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtqciidpye.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtgddrchtx.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gteucsqhle.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnnzeind.html

[S06] C：字符串比较
来源：http://dali.316326.xyz/Article/details/gtddqrpodb.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtypaygpok.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtbfbosqmg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtjjzvrhdj.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtilwotlzm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtzwuscdzl.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtpvcejukr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtjqtidbqw.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtgbhlmspl.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtdiqdfjop.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtrrxmiqok.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtqycpxvkh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtqyddhvkz.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtjgkbqctx.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gtchnrtuea.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gthutvskec.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gteubjtvet.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gthaqsgxij.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtikrkcafl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtxtqzjjqv.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtsaeqvscn.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnuovjii.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtfkgttxde.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtccnmpiqh.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtwivfpbgq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtkogysqcb.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gttddzlqxl.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtetspwnrz.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtxsxcgymj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtlvltycjs.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtxobtpsft.html


<!-- 参考信息 -->