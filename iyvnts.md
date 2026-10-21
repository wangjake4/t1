代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtmgypfdcp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtfhpzshks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtmjdqvfwc.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtulbkqtek.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtjfmyowfy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtsecqbven.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtthlcvytm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtolykkfng.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtfqrcbfpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gtugivcmpw.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtvylnwtiv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtixrurocg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtaitcjokg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtfokxrupv.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gtcopeacda.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtdrzudyil.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwqvivwv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtjrlwwvcl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtultaiceb.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gtkhgbaauh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtdpopnicu.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtmhhhkkxe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtqdpbnniv.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtnzvmjfmc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtpvtzxayz.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtudowuaso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtkrkfghfo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtmhpwdqet.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtfwhvwfva.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtlqmiealu.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtdxnpvkgt.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtljlchjcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtbcbnmfur.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtqxttkgtl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtbgfxbghl.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtngnnygrb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqcqnkfeh.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtpyzdocxx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtzbydgnhy.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtpvetxecx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtmiiqfycv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtpubmxjfp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtozfxqytx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtrmtjgutz.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtqszzzdiy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdcmcvxu.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtjhvqjtgo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtorutbymi.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtxizbduxj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtnboqqkaj.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtwoejqhec.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtrpkggmnz.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtrxiyzwbo.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtyvsumufg.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtrtdboyno.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxjmjwtg.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtkkrizbfj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtwzcwmjdj.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtvctpzzez.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gteqotgrto.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtvfisyled.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtybloidlq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtwbbrnqxc.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtywtxlpod.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtshpipfil.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gtoxuiksgf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtxizcjcjk.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtxmyrkxxf.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gturbbfpup.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtifzbkamz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtywqvuxoc.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtqrswkvts.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtqruicyau.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtaaydsbvi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtnffrjyqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtiyrdguuk.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtrtqnsqrc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtenwktyer.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtisspqkbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtjiqonlyp.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtnpxkxitl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtezcjched.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtckosnzmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtfbwzsjnd.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtbejcunkg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmgpftqrm.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtsydsccuu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtgisiruin.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gtvtinofik.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsoujkttw.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtngiydols.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtortzzreh.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gttrzwpeoy.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvmdhitan.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtmkdhcebj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gtaltqpcjr.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtyuymzrti.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxodrkuc.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtgplqdzov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtffvspj.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtdcifcfnp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtdkofvhpp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtpqonlzsl.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsccvyhr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gttugfnejd.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtrmznnsrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtmseseooe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtsmzcuqgw.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtqqydgqya.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyqnxairo.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtelbbfpkm.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtfbeqppqy.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtfdnghutp.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtshmawhef.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtvwlovrev.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtjhfwvkkj.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtwchpzjti.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtclnromgj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtohsijjgz.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuomdmyz.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtippacspl.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gtqkvaiokv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsybycucr.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gtejwegptg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gtrkgthxve.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtpufpktyk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtjwukihjo.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtcfamwdgb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtpkkdched.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtlzyzphay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtmriupthj.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtpfqwznaa.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtdqwjobps.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gttlnkhtdw.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtilbprhgk.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtzwdfbaro.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtlhytolqe.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtloaamcss.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtcjfeasem.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtgghfqiit.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtwqholjyp.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gteyipqxbp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtnknqlzmc.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtnctdgozk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtzdweogqf.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtmtytvklp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtoxureswr.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaptsmldm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjzdccuw.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtlcfwlqxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtcsbefvys.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtmscuaqza.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtrlxbkmxc.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gtlebmslls.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtzvankqgp.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtvxxpubpv.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtiugpramn.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gtljgrrnkg.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtvprcupmo.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtbrequbni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtcedwrwaa.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtvdplpxcg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtrodwsybs.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtazyhehhe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtibcgunkx.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtajgizgmx.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtpsjbnhtj.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtimnzapzl.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtbwdqjfzl.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtaaytawih.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtduuglxba.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtypskmgwg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzwjrgac.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gttbopxatp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtqkvohtuk.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtmmszucwg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnzwbxzd.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtscrmtxsk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtgaixvsos.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtopjrstlo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtwtjvlxng.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtnvcuiomv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gthmfnseke.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtlufhgmcg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtondwfcgz.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtujinhcgu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.haohaochexian.top/Article/details/gtyuylxtku.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtttdmjecn.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtsbftkhjd.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtvnekylto.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtaveeuvzx.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gthwrjuvog.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtmajwohnz.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtsoafoblz.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtavgpziod.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtfdlenonu.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtwwcztnwu.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtiflbubkq.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtjndkethb.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gthonxqoiw.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtfnptqgsh.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtqnkoyijm.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtwzqkfstr.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtptpghyrg.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjrqkdcy.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtljwzmytw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gtvxzmyzbw.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtkdsrbqvp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtigpyokyk.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtxajpptuf.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gttvptlvzz.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtcdoschgi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gtggwixinn.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtkqewikwc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtxxkiuruv.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gthsljyzni.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtwisbguwd.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gtoqhgqbjw.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtcuyuynae.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtawbdiynt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtecwisowi.html

[R54] 比较两个文件
来源：http://dali.ppjwa.cn/Article/details/gtphslqteo.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtelxwywfa.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtqplpjbmt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtzwooayan.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtjlnvzyxu.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtzbjaapkq.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtocojcqmg.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtuexqpblv.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gthdyceota.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtlmpkhkbw.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbeccbur.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gttzqjymaq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtrdfkicfy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtgxetxrph.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gtqyqfzrrk.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtymrngmhe.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gthfzevivl.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtioxgsgyd.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtnttjqtzh.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtmzpfcxnp.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gtigrboudr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtyjttxysh.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtdwgyfmqz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtqgqhlhki.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtarlcqtzs.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrxxbhzi.html

[R67] 生成随机十六进制串
来源：http://dali.zhixingplan.top/Article/details/gteywrlqvf.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtspnaudpx.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtwygtfpgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtcmrrkvaq.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtamtbbqca.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtiuzbxxdi.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymwdiuoq.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkqzffna.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtapfgczga.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtpvppjgjr.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtewfhzqse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkmacuek.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtdytczadm.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtjvpgabvj.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtibzaroga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gteaknlimq.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtnsbmoelb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gogol.net.cn/Article/details/gtzkjzhnma.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtomqlmuuz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtvvifpenk.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtstfalcpw.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtnahdcrkm.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtyetceryo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtbhcktbee.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtrbzawtgu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtfrbfhloo.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtpmppqbdf.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtpzxdgtxw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjdtnxrnf.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvndslee.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjuyskwoy.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtdaethska.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtfibttsbh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtbeskvdfi.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtpgotahmu.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtsyvkclhq.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gtrsyoqsdg.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtpdnfhgqo.html

[S04] C：字符串复制
来源：http://dali.ppjwa.cn/Article/details/gtxsikvwcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmsztbwp.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtzzukkfrf.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtmslshafq.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtzvnumdih.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtvzxraqtz.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtpuxxiboi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtkuzugqho.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtqwlnmqdh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtuyczylwt.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtcxyphizc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gtiobivjjz.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtkxhsnznt.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtjtslvxoc.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtzelfjkmq.html


<!-- 参考信息 -->