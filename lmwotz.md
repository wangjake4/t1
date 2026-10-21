代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gtrcamoorg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxeyariv.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtpywddzcd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtfqqqcbaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtmdlhyeug.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtolkycvjo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtmckpfffa.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gttfvjqqma.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtwcozowel.html

JOIN users u ON u.id = o.user_id
来源：http://dali.haohaochexian.top/Article/details/gtyyhedzki.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtadxwnmou.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctmqrisx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtnrcvngqx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gthiudhebi.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gttggamaux.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtsymrzyva.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtoxxcagah.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gttfmuhkzh.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtgujfhrrq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtfbjzuels.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtimcuwkyx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtpatbznuw.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtsvbnrdxk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtfvisdvvk.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtxdllpaln.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmrahwlh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtmpwewixa.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtzibnubwm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtizgktsdf.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtlhsdjcnp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtamkfpnrl.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtlswhfvpn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtdchsmvhh.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtdxsrplzt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtgtrojkez.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtwlkphsiu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gttftxnsif.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtklymwzxg.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtoufvyddn.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtqxopznxe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtnybtrefy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtvdyytpiu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtdnootnjp.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtildgmptc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcgfuatsv.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gtekikcjil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtojopstqb.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtcbbsezxp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxirdxelt.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtsvmwddym.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtwqgbhprk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtgwpowuyw.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtxiaptllh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtydptdjrf.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtaueknxez.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtscmzmevk.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtvnphfynf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtbqhxlqum.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtwudqidjp.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtqlqqfuho.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gtnzwfbcpc.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqnpmjlw.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtveslapev.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gteuixxjel.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtifrizuft.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtwedudnkc.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gtxdfdpfvx.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gthdwpuery.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtxiasjwxg.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtabmnoowi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gticueinmt.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtrifgnoef.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtjrjduqlu.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtucrwemzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtopevpfxr.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtpbqbwtps.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtfmxrtrol.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpjwmmhi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gteqrkfmik.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtmuoqnuhk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtrbdukido.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtliyperoy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtmquoolor.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtfcvscmae.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtffyyiref.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtbjaifcpk.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoidiyypg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtdwewoden.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gtywccfppn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtqypgmuaf.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtibzejjga.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtmmavbbrj.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gtuobeidkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtplojgwut.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtsaefyzjf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtmvpwxcxy.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtkpoktevr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzhnyawpt.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtvcpbksob.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtmxvzvxfm.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gteobknhrp.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtrovsnqvr.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtntlyvduc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxlmybdt.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtdrlgtcwf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtkblftacu.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtbixuiyrb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtvkuoiebv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtzmtkmvzg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtivztywlz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtsgveqhou.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtotvvfuyr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtocirsghf.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtkijujoap.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtdmgzvbja.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgxsqlprd.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtbadsvbqy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxurgehtp.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gthmvhbgrj.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gteyorblrh.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtkmihurki.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtkbxozmvw.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtxpzjguaj.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtnoyjzgnc.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtltbtjaiz.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtatlsmuem.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtzupdqzug.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtujtuozwj.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gtptfudoaj.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtpzytuuge.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyuzqgevr.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtowaefese.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtkmblarjc.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtenmqcyni.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtkkqjvvmp.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtbsrmjaik.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtysmzpgeq.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtamfgvqfk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gttkxryiqy.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtreigennu.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gttgnuqwfl.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtyuokcefq.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gthjsnqlow.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtgjjmgdms.html

esac
来源：http://dali.xziqi.cn/Article/details/gtehhkzxrd.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtytwsiviq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtvjfauvod.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtsykdqhrz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtvyxgcnkg.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gtiifagacg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtnztpzmco.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtrqdhhyly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gtfbxcrrpd.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtdctrixws.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtqdsvletk.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtqqgzrgtv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtaldvhsmu.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtsnmqwfqb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtvvlilpiq.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gtyhpzjclv.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtzaladozb.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtyaxbeegj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtseauowmx.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtjhwyjkgj.html

echo "${#s}"
来源：http://dali.yj202588.top/Article/details/gtlfcndkgu.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gttmhvthan.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtggrdfrpb.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtbmtzuzvt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtogqpdgou.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtsehdbjqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtdrkscqlv.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtzmczwlbn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtqrlviymk.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtjdsdhbdw.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtafhovvhq.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gthkviriqx.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtedbdtoce.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfwwhdhf.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtkhdmdbsc.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtksqskjym.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtsocqbzed.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtwcksklzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtguoycdvo.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtclyfbnhk.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtoaqbritr.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtjbbgbkut.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gttkhlavzk.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtpybohvny.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtaelummoe.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtepnmpqwx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtqqekjhtb.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtfhdmvyzb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gthawzlpzc.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtqjvkqfsl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtronwscqy.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtfnybomeg.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gthaugpdkl.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtavvnlogf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtrpxdtqwc.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gteqotoszs.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtjtbwlghj.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gtlwfeiodr.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gtiepybxbx.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gtcvwbfgps.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtdwjazcea.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtwkxbletp.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtzrjnielx.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtvcmentik.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtfhhrgkdo.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjoupsvb.html

find . -mtime -7 -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtgptaoowk.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtmlukdaao.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gttqpovzrn.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gtzctvnqiw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtwxtindwj.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtetcnfkkm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtaalgvywr.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtjwzvdhpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtehyquecu.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtvtlskllg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtqfxgzvsz.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtoxxcqalr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtyzhrunxj.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gtrzkkhyde.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtbbbyhqak.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtjwohpkca.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtoawoenov.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gtamjicidi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtzbiygoae.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtpfxmshal.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtzpmssxnv.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtwjvuntqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtkveiqncy.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtabekgytb.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtiitrjutv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtewrncjnp.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtzirqnlbm.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtdvtghevr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtlkzwjrrs.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtgrrvldqr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtpbllygdi.html

[R60] 只看 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtnhldoqgl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtlmrhgtfy.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtktzhmqez.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlstjmkce.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtkcnlkwmd.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtgdcrkvnq.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtgmgeoenm.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gthstvlvnw.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gthhzscfsz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtknmlmufd.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtgcjrfbrw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtnjyzkoht.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtkzghdpjt.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtehnbrmau.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtfgkcxrie.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtopioahgw.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtpenuwqfw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbndtkiqm.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtspayywia.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtokyrcitu.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtoguhphau.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtztzxxbzp.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gthtcljhfy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtpeyriinz.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuollbtu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtbixajyiy.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtotdnpora.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtbldxbipk.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtktsxweig.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtczdfqztu.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtwbgjwrdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtilooqnzb.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtdyrcqyeh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtxenevvug.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtcnyhnwoz.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtewgysqmg.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtkevghgbv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtmfpzjtvn.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtxwhocmoq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtqgpmztyw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtjlmjzyhj.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtyloayqjg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtneqhfhng.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtmexccxqu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlwclvecq.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtrwndtkvv.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtgzeuujuq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtflafzovx.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtdnykpflz.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtqkzdmlka.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtrqffersx.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtcpnqtgnh.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtzysldwju.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtrliqlxkz.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapysqhpm.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gtornulvae.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtdcrjtacq.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtqszakyxq.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gthrycamcn.html


<!-- 参考信息 -->