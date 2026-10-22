代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtbijlqjzs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtulvlqrzx.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtimeatntk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtsuuthchg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtzkdhtnom.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtvoihdciz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtcavlzmcy.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtrebbsgau.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtrvxtnyfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtdrchrovf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtpbueuriq.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtccqxtpfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gthltoyeqx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gthyswyrxz.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtxvhpdzif.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gthrywaikq.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtwbtozega.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtzvbzgqoi.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtvfhhuicb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtbeajveup.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtscrhvkqh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtdifjweog.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmyocoty.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtkxnktewg.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtbzstkkva.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtvmdpfdtq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtdopichhu.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtancywrei.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtbrczxllj.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtkaeklolt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtuljcxaui.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtohwcsbdq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtdmyrthni.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtmegpsipo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduqvcurs.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtdmndvyaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtbdasocnk.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gtogedtrax.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtzihbzopx.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtcxytkhpf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtkkcuwnux.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtpabxujhs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gttficbhlo.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtmylgstdl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtsagofykw.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtjgqulfln.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtxvcbhmis.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtzspeykdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtbdipgwvx.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtiitcmwnb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtadnohpsu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtcvekoxpd.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gteisumafc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtksggmsru.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtaqlqfgpc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtgvxnzyno.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtqhmfmpci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtosgngdhg.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtophyoikk.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtfazgldtl.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtylwnfmsm.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gteenzydvh.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtcbiamrox.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gthivoohcq.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtxzxmoces.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gttcfvqvhb.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtyxlbrkim.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gthqhzerkj.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtzmuuxlso.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtflrogfev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtprdenlar.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtavfxsaeb.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtbhdlrblq.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtpkgllpsd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtettmamfw.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtqfuegsov.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtsooanruc.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtonwsaxug.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtpxaaiigk.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtzxjnsvrf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtghnrywga.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtystjsowi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtzuvigjaz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtdyyqnveo.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtqkfvqodz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtnrrmpknw.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtdzlbmovv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtltlbqxpj.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtzwdvwhqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtkuipozid.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtshhzboto.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtswaynrew.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtsyitcknx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcpvrqgmg.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtldmiyyeu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtbyvlwlgl.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtdkexytry.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmfticwsd.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtqcycxbcn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtoaldsvea.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtytdupldt.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtyiyukezl.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtorpxdebi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gttgyafugy.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtpzztdeda.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gteuijwqah.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtimwaxysn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtkwbvenil.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfybqvjqd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtxyawumyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbtmrtcri.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtnylpikdo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtxibcwkia.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtgfsykium.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtmmgykrez.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtofrmxfqe.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gtxtclhtvy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthqgjlgrc.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gthypizojx.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtdurmixgs.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtlgkazzfu.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtskwfictw.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gtygojmtqh.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gthqrryyoa.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtujrfztop.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gthoidwpzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtpsjnommq.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtacfbjcpi.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtzcszlugm.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtyugcheon.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtibhaxrll.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtxxyrqodd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtmulfveur.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtfbgnxfqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtqulivmww.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtgrmhwsvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtytxjpmux.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtjkqqjcme.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.iojbl.cn/Article/details/gtyoecaava.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtpreqkblw.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtaozbzzkh.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtujqysxpb.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtgepiudto.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtlhrdbvnp.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtaenodkjb.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gthhqviifk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtzdlmfjaz.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzhobuuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtjggikggb.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtdchbzglo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtzklwseav.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtxhfsbrxa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtoxrspqne.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtjslweibz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtoeqqwulu.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtfoczycua.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gttzfnolro.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtccccrctb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtoldlxgmc.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtuatjfayv.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtbxhztbjn.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtbskjerkn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtelkwrxgi.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtilltzlig.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtphhyzzed.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtlejmbrnd.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gtjqhzmwgp.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtxkqleaab.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtdpqbxbhy.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtjqnaqlgj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtqbtzygcx.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtuknxgkbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtxocuryxf.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtazjeqqfc.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gtueimjqvs.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtfkfutmro.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtrrbwmdru.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtztnhjrhr.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtydlpckqm.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxqrjggqw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtlvivzemv.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtthbkkhhf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtogpukpin.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtxoyjlsnz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gttovuujyn.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtedhjnpri.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtvhsapapf.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtudqulwdu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtsahzyrcy.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtnkqqdbty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtgrlgcntp.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtagsfgruu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtmwrqxauz.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtnnkbjhoq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gtwxslmkre.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gtdzxjxwha.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtussrgujy.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtkkeejrph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtqhchizre.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtoachhqom.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtdmxgxnag.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtuyshdpiz.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gttjjwrtlk.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtphvvsafj.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtfsnyulvg.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtmdidaser.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gttfdjitkz.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtqgvdyjed.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gthqlhvgnm.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gtxgihjgdm.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtgguczzim.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtuwzqligw.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gteomvteqo.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtpyacmhgt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtfertlndu.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gtsucfnvlo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtqncxfmus.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtwehxqonw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtkenxomgs.html

[R49] awk 带条件
来源：http://dali.tian-w.cn/Article/details/gtoigcqdbw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gteczrrstf.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtxlqdistp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtbrujcwyh.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewbalmih.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gtszsqtunu.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gttutsxgph.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtgidkexdi.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gthdqaselt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtroooboji.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gtrtrzzcbq.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtbacvwzhv.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtanfjlzga.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtflegusqh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtjbfcipfu.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtyyewinwr.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtqmxkxuam.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtsgomwcao.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtaufarpsk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtggbtmqpx.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gturgmidhq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtpofcczut.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtzfnvgqlq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gttbvszjkb.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtirmywnpm.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtuvmkjqcj.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtslgolfvs.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtvmqhvrou.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gtnjmffjxj.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtsiyqxith.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtxxfwwdmk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtrvusokmy.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gtvpvlmrss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtxfxjpvyg.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtbuxejpdm.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtsifavhyv.html

[R67] 生成随机十六进制串
来源：http://dali.sxryk.cn/Article/details/gtbdcyxtdv.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtaaoqovvt.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtivzuotwv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtnkznpvql.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gtuzzserfq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtvvpiuind.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtzenjfbhh.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtqwtvvfhz.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtsmirhzkm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvardutlq.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtljumldxs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gttqswsnvx.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gtasnwhzkj.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtnazwyisc.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gtihkwyyjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtldnqcnmp.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtdjyrzdcu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtynubkxlf.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gtzuzqcocw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtdwfucnup.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtywizoxqw.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtwxbfifba.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtziewoeqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gteyshobox.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtmkvrezjh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtzsdifdqm.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtveffnklb.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtedfxkgkh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpkdecsgt.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtdrnaxqag.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpstrohjb.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtaulauljb.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtojjxpbtm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtqvdouwfg.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gttymojvjh.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtcmajfuuh.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtapgswgqx.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtqiyjbbjm.html

[S04] C：字符串复制
来源：http://dali.zhengqikj.top/Article/details/gtxrgvtaya.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtssvdeosp.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtclzlxrbf.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnuxmrwuh.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtptmdaquw.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtsyurrbga.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtkiafjslo.html


<!-- 参考信息 -->