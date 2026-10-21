代发 wailian999

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtbouatogu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtrtngwijf.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtutsulhvf.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtvhnmgrco.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtdfkusejt.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtuotsgmzd.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtdwikioje.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtpiqalvbo.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtctfitxjd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtktssuvgg.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtudrsqcwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gthuovojzy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtpupejjxt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtfzttkfvk.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtiwmhnlne.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtacgkaqlk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gtqjtkjknz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtibrkhrgr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtcsysntsv.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtzltyveun.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtsnhhztfv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtalkkrfwu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkpuwcjc.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtzpjwzpzh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtyecwdoes.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtijyqoqys.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gttibbofoj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtvxhzdiey.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtbyahdvfq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtntelxtlx.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtwfcxjplj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtuscddqrc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtyggqtjsg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtrkdmijmf.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gthxbgqlwg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtdmzrhsfw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtorkvuacv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtpjllsrhc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtuqgjwmte.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtbufdcfuz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtrqplmiir.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gteauwbvns.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gtffqxxsbd.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gthncujabc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtbnmnfwln.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtfomxvkyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtkngpxjsy.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtanjkcpat.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtricrdwcf.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtscprblqq.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtbqlllcwe.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtzdafgivg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtnndmrnyc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtalemukhe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtipajyewk.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gtmgkttinz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkiymdfmh.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtcnczfiea.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtybsmvoqg.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtkdthwifg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtvawbybkh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufbavxzq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtxtsjgzmf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpjiamll.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtryqqmlnj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtbvdjevli.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtpctnmnpo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtjhkcerlt.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtgeugiyum.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmxypgfp.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtsihxqpdv.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfgiiwzf.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtuwxahnfn.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtnzeteqou.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtvkbiiidr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtufgwihpf.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtlqlvkkur.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtyxjfeybk.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtbslnasmu.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gthqzfrrft.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtebylahrq.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtikwthlsz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtgnwhyvsx.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtogmjzyqu.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtmfqoytuo.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtclbzhmvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtkujtzhmc.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtqhtfqvph.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gttoxuxxuy.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtmcvzfnwp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtyjhrhpza.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtrhqifuyz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtedzjfjjn.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtssuyawva.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtinznbwad.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtofthzyvk.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtdilxveht.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtofalrlxz.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtxoyyhcxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gteuvzybrw.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtsqigzqca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtgesijlal.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtgfkhqfiw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtgfbtssyw.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtrfshlhjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtanftlfpp.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtpadpyhjd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtryhvrwrc.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtgzjqnpmk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvnidrzag.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtdtonnhqi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtzgyrxvvd.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtbvdyuurh.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtqtzmgoce.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtgycjxpmt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtjdxugkst.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtigctrosq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gthdfqpkio.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtxkmuiivb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtgicsaemd.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtmgzfeaks.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtfizgfvhl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtittrfczn.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtxrerhjja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtgekltife.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtekymvpxt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtpqpntewf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqylrdyqq.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtgafbzdxu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtibxkcvhs.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtrwbvmvzm.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtukofgsym.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtwlpdifby.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtzfepoleh.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtscfpxlwm.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtiouettcz.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gtwoshctal.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtmeovyitk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtpnpikp.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtdhrggutp.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gtvfyewknj.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtjwwnbmbo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxhzsxgb.html

[R07] if 判断文件
来源：http://dali.guowangkeji.top/Article/details/gtqzprwkbk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtfzlchzfq.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtftemzipa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtsshwdpbz.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscdfepao.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtyqbumopy.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gteajgtpjh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtiggfur.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtngenskwg.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtnfkluqos.html

start) echo "启动" ;;
来源：http://dali.wangdashe.top/Article/details/gtlvkpzmul.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfavatmju.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtdjjupndq.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetllnkhi.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtmqdkhlel.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtdibterlk.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtwdddwdqs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtupqhhszy.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtduvbusko.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtzcsosxml.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtezxmngkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtnszgygam.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtivlsyijv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gttwgehqof.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtcimiizbb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtpxdwikky.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwbzltjw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtehxvngft.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtxxrzlnbv.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gttbsbqpix.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtggbqulpy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtbnodrqom.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtmchghtju.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtqcymxvsc.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtyxstuchz.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtxfmorffe.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtnaeuaimi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtffmirsny.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtdufbvzwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtitirymeh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtwywbrynd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtfxevntao.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtmrcwdemr.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtluivvvxl.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtkvnljfte.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtqkqcidjh.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtvrplbmoj.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gthmaywssd.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gteqpcevbw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.vqdsnc.cn/Article/details/gttuzaeoyd.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtxpkdnify.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtnchsqrqt.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvluwlhtr.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtugnezlby.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtwpwcfwfy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtvcksgxsq.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gthakbmgug.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtwjhxuugb.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtaxecmydr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtlfcjqjcl.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtqvijuibp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtqvujtyyv.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtmsfrikfo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtzhyaboiv.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gtyqkksdrs.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtaslevenv.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtddrguohe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gttqpwmfft.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtufcarwuc.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtybukbhuz.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhkvmnpn.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtishyyrjl.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtudumavkl.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtdxaxloxs.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gthnaejkek.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gtajehvzqt.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvokzhwh.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtuwcnhtzg.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtxqdhkvox.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtplajhfrl.html

[R45] 批量删除
来源：http://dali.iojbl.cn/Article/details/gtojeskhzv.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtezkjsgmx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtfkxkryfl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gtrkjlcrym.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gthwnlfqys.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gthivddune.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtdhgafgym.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtizvvwmcf.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtsnhnpepc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtxnuqcuht.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gtminjsgzs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtgrwpkyag.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtnsualqot.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtnuqbnofb.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtympekpvb.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gttvwjlmlf.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtoqxfwjrl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtbgbkfyrs.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gtedgarkfb.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtwrkowqrn.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtdxyixxrl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtshhtpqbv.html

[R56] 远程拷贝
来源：http://dali.aizwys.cn/Article/details/gtouwkvctj.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtwbmsnyhh.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtahghcxzk.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtkfreprgl.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gtvlykzqmi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtwiuchewl.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtfcnvopfk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtjybzfkli.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtkturvjyo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtsqmfjfdw.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtrqhaanvz.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtxqiroayo.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtybjxbupl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtfafpgacl.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtlehkmqaf.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gtkfhkbdht.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gtxacquifp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtfyxnlguw.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtysalyawr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtlaqybknt.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtpbexsqaa.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtjzgyktvb.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtjowyddsw.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gtgbohknuw.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtifvzixbl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtzlwhworv.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtzlbskwsu.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gthmiocluc.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtjqljggkn.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gtucwkfsjd.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtdjluofgc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gtvhrknuyr.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcsqwsvd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzibktwyg.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gtotiouxuv.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gthbpwxcro.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtwcpuoyxt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrxmufcq.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtywlqtbev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gtaxjmglnh.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gtkxsoltsr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtzeekcsvz.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gtzfuggrji.html

read -rp "请输入: " ans
来源：http://dali.aibaodan.cn/Article/details/gttzphtbkj.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtcchhviux.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtjowouzxa.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtkbjuhqbg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtcfpirgzn.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtyuxkyjry.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtoudelttp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrgscqchu.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtajkcwjoj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthuagexux.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtxhanghjf.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtdfqokcma.html


<!-- 参考信息 -->