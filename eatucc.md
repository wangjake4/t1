代发 wailian999

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtrmzxvcfc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtfrdtfokb.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtfzsluesz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqptvlhw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtbygukiay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtowvjwlky.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gttrtfsajo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtaokzjceh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtwgfpxjfb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtyaddxirf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtdiiojliw.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtrugsaeif.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtmgsoalgv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtlovvjeyf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtmzzlyxud.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gtnnfthlfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtvxwybdbn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gttmsaubby.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtxwtafavc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtinuhgdoz.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gtvinywnbl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtrgvqzkzl.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtfdjuyawf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgedlyisr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtcixvrsoy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtnalipvef.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtqbpizwph.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtmqjequyt.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtottpyaxr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtklisyjlh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtelulqkdm.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtajeodllv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtpwzemjab.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtoyzhbamd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gttwvjuujm.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbubhoxks.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtkxxyupcg.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtfxmkjrhk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtadxazrqk.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gtjarvziiy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtjoxhygvu.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtehzcxeju.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtpibhssqx.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtyrnpfhgm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtzrfmewik.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtqallhzkj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtpjdvfeva.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gttfvczwvq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtwqyxblps.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gtahtraozn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdbezydjl.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtwngltoah.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtqbzmnqos.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtyycozlaf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwdznyku.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthkagtunk.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtjdogiipc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzbwiuhd.html

[Q62] 分组占比
来源：http://dali.ppjwa.cn/Article/details/gtaptazjpj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtbixsqurr.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtluiockmy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtfxtrdktv.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtsoijblja.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtgegnbysh.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtottpcvbe.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtkscvasxy.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtvxqpfflg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtoudsqted.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtgmjdtuhp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtupqljyef.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsgxjnon.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtpoozfjki.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyxzbvji.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtsrbppdmc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtqyvdwaam.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtxtyerfet.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtfjbnbjas.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtetcdsboo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gteazdqoks.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtapczwivw.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtogbqbyky.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gthjstakfm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtvxbylwzj.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtmchnlssz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtkhwxyocy.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtatyxqn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtisimntpv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gttzxbrphh.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtzwczvwbq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtolbisbsi.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gtzxhcvbmn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtnxogtpqk.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gtuogsulrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtmnvqtgnu.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtcggaihcp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtbwnnrdhw.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtpsmqgrlj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtclcjipkt.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtwaufyesa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjodesrft.html

[Q82] 字符长度与字节长度
来源：http://dali.aibaodan.cn/Article/details/gtufewsmyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtuehddcma.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtjqapumps.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtlcidknlr.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtmnfzrcrx.html

SELECT TRIM(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtxelqoxdu.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtqztjbicm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtazjanaal.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gtuvyfkonc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gtsjfpskjo.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtxbrclnsc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtrfzfmqsa.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtiqjumeby.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtiljekxbo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrpkemmez.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtsgqkyijq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtgvbkhuyi.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtgmrlajll.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtryilouoa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbwqzlfml.html

R. Bash 专题
来源：http://dali.sweek.top/Article/details/gtreamptrc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnjmwaegb.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtseofvmux.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtbrblscnh.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtieynktcw.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlmujaus.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtzrkrfwiq.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtauonifer.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtewhlpltd.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtllpecvmy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gttvtgddrr.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzowaynn.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gtgiptzrjs.html

[R06] 判断命令是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtwvtlnplf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttawitlyk.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtoltjtkvy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtgocfuygf.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtdbpwgizb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtnbznnsyx.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtpktmcfph.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtcznlfqxk.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtqcqmszuc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtfydirkdw.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtloggxuwg.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtraewmcjg.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtrvjwluvp.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtrhjwmdxr.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtzqenrngj.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtmfowceil.html

[R12] for 遍历文件
来源：http://dali.shzxlz.cn/Article/details/gtohopxici.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtmaixgbko.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtcmfhmwop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtkgjjifdh.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtlzzqbxho.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtamyxzmjn.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtebfbuzbi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtmiiisfla.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtbziyovwu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtckuvaliq.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtdbjgysxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtpnuugerl.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtnetvtdoj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtjehexcgm.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gtpmcxhcjr.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtmbabvexe.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtdbztmeyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtyjseudwb.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtexczjahy.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtqyrueuqi.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtkhvyfofd.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtlmijdfwg.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftzjsoos.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gtnxifjosa.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtwnyffcex.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gthxdjdiyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gtuxkytnay.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtbxzqtkio.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtjceigeeq.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtyypzeyko.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtlsviswsy.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtpyzthrcz.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtyoxkiqvg.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtlragjcbk.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtslvrxlyf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gtvgdajscc.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gtiniyesfp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyntdhjr.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtgespvgaw.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gtpgkdswgl.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtgzhvsfso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtgrrzevgh.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtqlmlacjw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtyoouyrrf.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtqoqyffhl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gthiyyalox.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtnboaalkd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gthfgausjm.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcjyqsse.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtewqybatn.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtqsdfwdyw.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtnydeieyp.html

[R38] 管道串联
来源：http://dali.shuidangran.top/Article/details/gtscqigsyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtwlgtizqb.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtvwsjkqjt.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtkxkxyffm.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtpbnvnctx.html

echo "log" >> out.log
来源：http://dali.jinqigfzy.top/Article/details/gtsamrgzar.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzbgntfn.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtgeedkxfn.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktkjblqr.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtipplzgwo.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtkzebjseb.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtvjdsdguw.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtrlxfttxy.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtdlxonhvp.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtibdzdpim.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gtxyxilwix.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtyomdmtzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gttkvrieyj.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtngffbiif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtytwtseou.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtyabhmliu.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gttouuzojv.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtbsrktgsg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtdhogyang.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlvknzlv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtiinvmhvi.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtjegoxjgv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarwabnja.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gtaptsuypq.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gtpzagbfqu.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtmfqqoazw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gteetnxknw.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtzuaaiewx.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gtuwxnavsp.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gthskklbnb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtlexxxsfl.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtqmcfhprb.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtfmmvokyv.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gtzxzruzxn.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtwcongsjk.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtntwrgpvl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtdwhnqumw.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtcraybvvv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gtfrgbnbwz.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtysgsqwho.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtosnmsyxc.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtliablfjm.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtdetacuja.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gtpfknjoeb.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtplukbncj.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmtnszew.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtblqirczv.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gthnsytddo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtnuvmagok.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtvnagdbrf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtektwjylx.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gthuxzyuqi.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtlnivmwtu.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtjjavjzme.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtexvrttwc.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtsbvhzqwi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtcqqtbxmp.html

[R69] 生成随机密码
来源：http://dali.yuanzhike.top/Article/details/gtemirevnx.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtyadpjeas.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllvnfiii.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gthauadraj.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtjvtmjnmz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtgzuaikyb.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtqyfwwmfj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtkdlnhdcy.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtrkwhzwne.html

split -l 1000 big.log part_
来源：http://dali.jinqigufen.top/Article/details/gtnxjumcxf.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtjyzwbenp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtooswkgsd.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gthlonrjdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtpqsibkma.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtytnhtpit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtcewomhvo.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtajlqvieg.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtffdeukzd.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gtwqqnaqgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtufwramtw.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gthshpgcqv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtqlqywofx.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtgdbtvaua.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gtdhozodkj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtalxdnkuq.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtoyaaatsj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnqaeiylz.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtpbhuoohm.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtgwzqpoou.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtjigmjnyr.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtpuvzszlr.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtqpcrlill.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtrknqwflc.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gtpbdfuoye.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtqrqihmvs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtlkilcmsg.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtmjbhetun.html


<!-- 参考信息 -->