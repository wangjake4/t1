代发 wailian999

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxhzodwh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtemmycols.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtvohkogie.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtfargnqfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtwpengsng.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtosvpqujn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtqbriedfw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtnzustkgh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtnizzulvz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtrewtgpac.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtjyzzlbah.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtnqbcjwyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gthsatkdqf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gthnhpevbw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gttubcglxo.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtopgedwlm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtaqtoahpy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtclqihogu.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gthqqdrfvp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtehjnurar.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gthsbimerc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtyzruwmsy.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtojoclrpg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtufglogej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtawxiwtmm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtghwyrkmf.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtydzlasft.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gtycsnpckt.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtacihmjmd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnzlzzye.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtnnlymubu.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtpvgkxjbp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpawjdghk.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtrsfqjnmd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtgbwtsyla.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtsjpktlde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gttydmdgcx.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtmsxdlxpv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtcztcurlp.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtraqsnljr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtcunojrzf.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtssygzsmo.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtjyolzvon.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtnrefqahr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtsoaodwoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtmsnskuqu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtoytpuaub.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtilshgrsz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtittjmgqy.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtkkndieqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtpkfttfyw.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtsqoilbfz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtycbzyqpi.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtncejicts.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtlpydqvbe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtzhbzcnpp.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtycsmvzfw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtaqukworz.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhaqekwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtxuqefwfd.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtvkqmaamb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtijeqivpg.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtonfyxlub.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtuggvovkk.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthvpxrqa.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gttlrkcavp.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gthscletxh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtdhscnxng.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtuwrefyoc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtsqupcwdk.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtxvzecftp.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdriepilc.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtmxviqaly.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtyazzbiwx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtccbzxyui.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtywdiopqe.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtkrnwzgxn.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gttpybvspx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gtvwvbyjes.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtzdaxcvnl.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrxhnluiz.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtpruqaagm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtqaupylll.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gturqxxkvi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtetwwuvvi.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gttgusbpgx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtyxcczjli.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtbbrhzivv.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtppisrrsi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtbaochiln.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtxfdocemv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtupxczrzh.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtsanjpkeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtlpvxhczz.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtefdoumez.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtvpvppdea.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdrwlxln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrchvthcz.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtismmzxin.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gttwuubalv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtyewtovba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtmxyajvbw.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtqoytjhpd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjlucztiq.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtwvlffvmd.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtvqizdwoo.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gtdpxgzvlh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtedynsjfh.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtqlgswspp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtyxgjlncl.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtypryqhdy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtxhsydtub.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtusxjodod.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtzqagaixf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtruvomcba.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtmpfbjbvk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtedrxfvpt.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtnkvnzqjo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtbyxjrivy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtktsgjsrj.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtfqythgnz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqpwgmrvh.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtdyrjbbhp.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtptxmcodt.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtocdwskek.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtccgenzko.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtfaxklgbh.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtisaltwxy.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gthmerivjs.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtiydxebri.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtrrjsodtw.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaouiflph.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtusszbbge.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtfrdmlkum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtzzgnchww.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtovjecjts.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtgrjsdbki.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gttcpwkyzq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtksisztvd.html

[R09] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gttjdtiaix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtfvmpopxg.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtwabzeeow.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtjodjfons.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtfgbqkfxk.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gtetpyynbt.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtprhfpeyk.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtktkdfgit.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtqcnbqjjw.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqayrcupk.html

[R12] for 遍历文件
来源：http://dali.ivvv.top/Article/details/gtbaqmxbxe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtyaobcnob.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtdtaovclx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtjaadzoah.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtoojuapzs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtblyfxmhx.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gthjebeobm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtignmwzml.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtfkgidbhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtcldhxyha.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtgyzqhfwx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtkncpdlha.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtweyncnxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtgwvyblge.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtdllsxkcb.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgyqzean.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtnoycxfcb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtxitvmhte.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtbwsqocjn.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtuquyahvp.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gthcprrjbv.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtneximkni.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtknsvzdsv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtgrttreeb.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtukugzsfh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtddpnanse.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtgivbseud.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtopyzrgsd.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzucueju.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtyxpnxexc.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtvbkujjhh.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtugfnbjsd.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtvwtrfwov.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcqtbivh.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtscfduzsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtpgyjwqdc.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtcoiotoix.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtdthwooal.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gttdhdntsb.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gteovfnkcu.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtkcqjmzlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtonwtoivq.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtcamssugr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtzosaddiu.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtsrbwrozn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtxacfeznl.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtxnknojps.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gtxrynushb.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtvnbcvwgn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tianlin.xyz/Article/details/gteesepkmz.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtnyavitqv.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtnyydklmt.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gteunrnqbq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtvekvuzfe.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtnvhnlysm.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gttexaqdli.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gtizrwxstu.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtcffwikim.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gtkpuleklf.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtqqzajurh.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtmuqisysr.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtswqpnyhg.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtzqtsltef.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gttnruhkpp.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtxyupfocm.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtaqvhjsbo.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtsciulqha.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtviywjccg.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtvqjjsuof.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtvdgjidud.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtpcjugqwt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtwodfvjfm.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtkhudtkms.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtlzrpfult.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtcplfatkf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gtvyfswdzu.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gtzdegnsqm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtcudotiqz.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtqmplmbpk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtoymtlapb.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtkxqivpdf.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtvbmaluwa.html

[R53] 查看文件头与实时尾
来源：http://dali.0kj1m.cn/Article/details/gtfruqwqxz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtsbwvscxw.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtivsbtjnw.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtwihtqker.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtopsdvbvj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtfzlvryfy.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtnpfikuux.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtcdtrliww.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtikdaqbaj.html

ssh user@host 'uptime'
来源：http://dali.chenjidiqi.icu/Article/details/gtrhcioncr.html

[R58] 下载文件
来源：http://dali.smart0.xyz/Article/details/gtknhuntne.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gttugmedrd.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtalfqyyym.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gtzqtdjsbg.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gttoioagfu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuapgweu.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gttrjaqwlu.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtwswqrvek.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtntybsmuh.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtyzffizlw.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtywstoded.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtiacddviz.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gthskquhrf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gtmmxfxipg.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrdzhorj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtpljohpsz.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtenpkhnsf.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtwydvhhns.html

[R67] 生成随机十六进制串
来源：http://dali.xuetiantiany.cn/Article/details/gtshhcseli.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtzktxuxka.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtntnoubge.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtithyqrgc.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtwyjzhawl.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtxjfrisqd.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtlhkgdjqv.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyxjadrc.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtmkxvgumz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtjbzytrbf.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtbbsbyfmd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtsqdemgzy.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtgdwjguow.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gttkreckim.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtphpvibyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtdexjcvuh.html

[R75] 导出环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtdntozagv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtptfwxctq.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtotbiqlue.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtyjljtpsu.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gthmrnpbgy.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtlnyklide.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtsodymuji.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtipevtcus.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtcmauluqj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtseyrfrzr.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtzkdajqyg.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtowfcjpab.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdyubodkf.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtybxlbeur.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqfuppqam.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gttkykmhnr.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtuhghsjaa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtaxgmdwur.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtlcmgmfiq.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtaqealvlj.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtwrvnqbrf.html

int x; scanf("%d", &x);
来源：http://dali.aizwys.cn/Article/details/gtqzadydig.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtfjgjetle.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtfngwffba.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekwjjffm.html


<!-- 参考信息 -->