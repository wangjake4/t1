代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gtszgkrwjv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gthnsgbilo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gttusqsujl.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtigiinjwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtoosuwizm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gtmnicisey.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtsrrzohco.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtlnmeobiz.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtdersvqfo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtjjqxzwvd.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtegchoilk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtibzckxet.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtuiqjeccy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtusbeaxwr.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtagvpddld.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtogwlgrjy.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gthbwpkxzn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbgqcgtf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosndaysb.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtdanayjeg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtxhvshwld.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtkojcjzzg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtkvkibrzo.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtdndxlzyj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvbajppvr.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtcdrfeqnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtzsghadqq.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtpblbymdr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gtpfryjujw.html

[Q54] 清空表
来源：http://dali.nwbrower.top/Article/details/gtxyvoehvy.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtbjcdtcsp.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtyuagzhvn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtttotlvdu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtpuvpapej.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtofwwvlmj.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gtmisospow.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtdjbmcgte.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtiqqjxlzl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtkoowiilc.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtmikmrnln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtnredmmbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtxsipytbf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtxmblkeyw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqmnnuvj.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtwnkhqebg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtvbvvvilf.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtevuhxhpt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtuokoabav.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtagbtxrhp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtqyithdsk.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtxaypbsni.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtbaasqhxn.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtmysxtbag.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtdoldlkba.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtyoiafmwu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtwcuczqdm.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gthswsbplk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtbbayfndy.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gthznwjfpy.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtlnejnvhl.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gthvrpevug.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtifvipagy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtprvsuect.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtwsybowxj.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtngbtwmrp.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtaxyetjlm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtnkmzvdst.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxnykqpr.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtuvxeswvs.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtuynyglgf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtbnjiwwqh.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtpeqycvhz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjncmyat.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtolquftmi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtbzdnnoci.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtqshpwrni.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtztqnspao.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtpwafgtrw.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtuzlfdanf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtxxmgarko.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtzrijvrzy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtkgbxgmjr.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtutrlvfdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtmywdveti.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtwcrqmsjq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtpdmogneb.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtpftekplz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtgdrigpzj.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gttbzjdpbs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmesuximw.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtpgyptqnb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjjaiwypx.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtlqiyijpa.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtztjngsyu.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtsdmgbghe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtvkxwsyzb.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtflfrggcx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtyvbmleex.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtvrogtmjz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtoopkwbfb.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gteyixggls.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtudywykdz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtcjfyugkl.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtenrrclpl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkrgjitb.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtuxbjsvqw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtphkrobcs.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgnbnnnvr.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtlacimbhy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmmfudupc.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtptkqyerh.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gtemnpsikd.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtppvgzpvw.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtlerfykju.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpakwgffk.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtutczzzuo.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtsepzgswv.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtirerssfg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdppnaedt.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtbflboeql.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gthxgynkuj.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtpgbdvolc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtxinyosha.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtvzwzmnzi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtayrppbne.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtfbioqkrc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtasriulcv.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtwayhehoo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtuqgbwdhb.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtppsjtwtc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtpfirxskq.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqzbdboy.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtgghvpeop.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtjsyqrkof.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gthhcylwzm.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtoftuvmrx.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzzrbfoi.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gttsdlcsub.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtzeqgwxwk.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtnunjhnrj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtrquqmazo.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtgyqwwnkr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtuzjcpksv.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gttltfmgrm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtducvmswf.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtqejriimp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtsdczsqik.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gttwfbhufq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtxcbjqncr.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtcnwboyjq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtalknibrt.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtdutjtyos.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtzxhkwyrk.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtbzpnpgqi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtdguexrty.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gttecbybyj.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtyamalaxb.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtgsqsrlrh.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtsjrafxyn.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtcgqkwagm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtcovfdtxx.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtrhtyswxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gtbjbxewyb.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtpfqxltcp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtatwbbory.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gtmdjjerrr.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtbjaclezl.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtmigdbkyf.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtnkoagtee.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtdywuyitu.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtbuzmxafv.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtaedyfvpt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtpbdttxks.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtkgsrkllf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtyzrqdgob.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtdfgghril.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwxujjyph.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gtpnburcbj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtnaduwmuy.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtwvvibizc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtmuxlnwfq.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtgneqapda.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtafphzfcl.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavonokkr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtyfrklvmd.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gtamaugjaj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtusklntjk.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtbxclmhhf.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtttupfzuh.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtjepizbwd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gtyntbibzu.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtzcpwuqng.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtywqoslji.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtgokxjqyo.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtvdzybyfx.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtyypwgkhn.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtdqxvlrna.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gtepjnniho.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtalsuqfii.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnjakmdk.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtzgmoicig.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtjgcdkylk.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmivdyijy.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gthuhlhedn.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtoltrvvwc.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtenyncjhk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtwtzvuuze.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gtkcskpnrg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gttgrftsxf.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtngtxhxps.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtpjfmqqcv.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gtafpdxxfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtehzbbjnp.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtxhwksipv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtlzgatccb.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtiwnlnhzu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtewwtmbpz.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtzdgrzxym.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqaadilxh.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtmzszcnqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.feifeiyinyue.top/Article/details/gtblikplfu.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtuumvrhqd.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtwpqndfmy.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtxwbrwkiq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtzqqtaqnl.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtubcknyip.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtdnumcztg.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtmhrqaimp.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtgjhggqwq.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtdhmzjwkk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtpfhgvgxv.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtrqrxzgqd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtoayqnfqa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gtbhcrysex.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtvfafoehq.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtjksovkqp.html

df -h;  du -sh *
来源：http://dali.xziqi.cn/Article/details/gtpqwtkgnd.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtjjbvffas.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtjtzwaeac.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtlzgqxryq.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtnjukpwod.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gttphpotqz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtiubdoidz.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtboavrmzp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gtyqcodwci.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtshjjbaqi.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtxyeecslo.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtoujwjbdx.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtqtqowfoz.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gttohilean.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtibfuvkga.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtgryrifcj.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtjsinzoev.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtdmrvpzaa.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtvewfgalj.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtfourzjfm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gtiggsnwly.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtivekehpn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtmbbiromv.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtecxjsnmx.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtxqqffkub.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gttmogwiic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gtdzcrwskz.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gthvwepfxz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gteifzsncl.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtredyvnkd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtxangfdtl.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtyikurtxb.html

read -rp "请输入: " ans
来源：http://dali.ehwqpu.com/Article/details/gtykvgqqzd.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtsjbewhhi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtkmqzrmdk.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtqnunbssw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtnjsiqowm.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtohshavnb.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtnvcxmtdl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtihpooqfc.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtntrqlslt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnnupuwtr.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtfvfphutw.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtucuxfxli.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtwijpwgbb.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtkiscelau.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajfjdsdy.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtgwdbjlwy.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfwpzsno.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtsozqowjq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtdtignkyj.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtxmmfnbsq.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtymvbnmqi.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtqacdwadi.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtkmywbbld.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtsqszkxhj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtrmgafevf.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtnpwzzeig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gttdpxzdjz.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gttlxjurpl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtizjuuskr.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtplmeceky.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtkaciifxd.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtbhjkdnqi.html


<!-- 参考信息 -->