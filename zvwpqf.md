代发 wailian999

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gt2hxupoasz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2vprhzzag.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gt2qzczcqhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2upntexzo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gt2bsdmiggs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2muxxjcxr.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2xnxmkxre.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2dsnvxfjq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gt2rlexbcna.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gt2nimjdxse.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2laiupwpd.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2abqbxrfz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gt2yksmbgxs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2ilnyloni.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qofkwkzk.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2jmkostjo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2qgjhiguz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2thpzuxgr.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2wdjhdstm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbbnlmto.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gt2exmoncnr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gt2yiycuraa.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gt2tptmcsmi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2hppylvdl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2yrghifwf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2iavtklsx.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gt2kohxnzfa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozbwablu.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gt2fpakykyg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2czwswxmm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gt2lxycgixq.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrdqbflp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2eyqfaeck.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gt2fvccdozb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2ktcusftj.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gt2cbdpoxuv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2hgskyxnm.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2gzfkjsox.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2beimutlu.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2badzsygm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2skjloxmk.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gt2blefxtnu.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2hkeyywax.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2stbmmedm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2imylcdfy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gt2itoeloew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2zfrxizrt.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2nghmfivh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2szhfjvij.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gt2ydpbafto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2hjftnasz.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2zbmkzyfz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2rvhekyap.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gt2ufobbleq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gt2zzwbinba.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vnmsbhte.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gt2uotafwid.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2ayaukpcm.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2uflullaf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2ytlsisgu.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gt2eppdatuw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2scrxcvqa.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gt2oivobucd.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gt2guamlvwj.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gt2sngwzkxl.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gt2hhrmisbg.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2zpcaraaw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2bqytxrav.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2wqrtizex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gt2nbuadwms.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbfimqzg.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2fuhneezm.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2fzhwhtjl.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gt2agkijojs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gt2lxeuxeqx.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2xvtpaykm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvvggtd.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2vbhkswth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2nxpskwbw.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2znvqfbhd.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2kgtpmnjx.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gt2ypshubqu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gt2pwcoqbpq.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2qhssaovs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2nbmzeziv.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtsqddij.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2rjyiguwt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gt2ymkxwycy.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gt2azrrgtsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gt2bldrgprj.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqctmtvg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2vgmcwnnj.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gt2tmmadcni.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gt2vndfxwqa.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gt2rfobpbdv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2uxuhtmuy.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gt2lvjfvfxv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2efxuqjql.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krazjbgc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2dkmnhvtn.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gt2lgsjcedj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2djterlri.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2pzblvmms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2gqorofln.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2jqpmyiic.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jjmjbnpx.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffuybosp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2wnuipbjy.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gt2lwmakobd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gt2hlrhljph.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfascghm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2qejafwud.html

[Q88] 行转列（条件聚合）
来源：http://dali.kuanghao11.cn/Article/details/gt2alfayrpv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gt2jbsxfwkx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2luqoomlp.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2fstiitmq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqbhokdb.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gt2onlgrqwt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gt2mxzfvtho.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mlvqlyat.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2pzdokmqt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2knzwkcks.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gt2oxzcsxwk.html

#!/usr/bin/env bash
来源：http://dali.ppjwa.cn/Article/details/gt2lotnbroq.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2dutciyig.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gt2vclxmfwd.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gt2wvzpbwzi.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gt2tmabwkqp.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gt2jlfxpvyf.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2lvkrnviz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2fpcjupfb.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2hcabxubq.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2hrumrdpr.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2izihgzgy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2zrovwtbp.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gt2mwhzbwcx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gt2ypzwtjsw.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2stelgzzm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2ydbopyzw.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2ywhmvpfs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhppfvno.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gt2zxiiqtga.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2wblekpue.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gt2ugtecshb.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqcrlbef.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2rgszwvhv.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gt2kfdgsulp.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2ykvwjqmt.html

esac
来源：http://dali.yongpay.top/Article/details/gt2ixluapjp.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2xttqvxjx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2lnnfysec.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhhsjmrg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2rtpsiijf.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gt2jrakcztm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2btrlrfsu.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2jpnyttwi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gt2ttosbcig.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gt2fiktzmwb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2tgqhwkqj.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gt2esrjfelv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gt2rscphpsw.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2blrsvkrh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gt2lskvdeuc.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2ypecsoji.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2hpsoyriw.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gt2xsscjxfa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2nptedhuu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxomvlz.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fejpwagc.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2uuaherly.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2motrocmd.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2gmwxsnch.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gt2eauqhjew.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2fewcndnf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2fwhntdvw.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2bcvcvtgh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2rmqjdema.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2tfyrtetw.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gt2jfqfqgkb.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gt2qjnucrco.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2ekyvqnsr.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2sndxpdis.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gt2wxappfhq.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2fzbkmlvb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gt2enqhvdhl.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gt2jcqydijs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkuckikf.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gt2evlbmbbb.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2kllxjbbg.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2rivprhgt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2utjolwmd.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gt2bgyheggv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gt2emqmgllv.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2iqtskvlp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfrjwjil.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gt2pbhihtrj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gt2eldxdubu.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gt2mhezwkid.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gt2xupoosxf.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gt2txwcbzkj.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2ueqqoagv.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gt2sbivxagp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryjekwlc.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gt2ogsluvrg.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2veqybnll.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2pzumiuqf.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gt2xtbgnaix.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2gaizmjxa.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gt2mklhaqpb.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gt2tduhsnja.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2jcjtgqmo.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2fghbahku.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gt2kjdkfmpk.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gt2vkbhasdj.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2qghenldz.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gt2knpngnoz.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gt2vlnnsisu.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2nubqsesc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gt2rnuxwprf.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2qhzytxso.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbguklwu.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gt2xzhyoayc.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2rdlndmki.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gt2bblcnfzt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2pxxkslbn.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtvfxgoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2frqqwqjf.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qctlxcei.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2ewlkrnfy.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2ztxnwwry.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2fxxcurcn.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gt2sbqwkrfj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xylfe.cn/Article/details/gt2wfosqnqk.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gt2ioqdoowb.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gt2kwmzjhhe.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2xqfwbwsd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2numwgkme.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gt2tszlmpyi.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gt2vigjeaca.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gt2luxwwuwv.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2ekadckuw.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gt2kheuxjna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guannengcc.top/Article/details/gt2wfcbmvqn.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2ddiszgtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gt2xnrghfhv.html

[R60] 只看 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2tbujhdhl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.c1oappe.top/Article/details/gt2mpldjwsb.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2wfgzctyt.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2npbxkukb.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2adjuhisi.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsvqhdmi.html

[R63] 内存与进程
来源：http://dali.svipenyu.cn/Article/details/gt2ltrsfbxe.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2yjcgqlqr.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gt2eenfrnez.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gt2bcvffybo.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gt2wkoffeur.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2tvtezugm.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gt2ncognrhd.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnxnljsx.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2snfpesmb.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2fzenszwn.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaurdzeu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2kgvmbsmx.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gt2vswlvdce.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2lmemvdxl.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2zxhehqzw.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gt2hcomzmqk.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2lgfniryk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2ttfxmwbn.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gt2bntdhbwz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2cuhrngwe.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gt2sjyouzwo.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gt2zpiwupao.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2iudvcngg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2ixxxxvgn.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2kisuhfoo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gt2xversztk.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gt2ovykrpug.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2zxeeeycr.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2jsdupaow.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gt2chggjkib.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gt2ajehgaqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gt2ksdygkhw.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gt2urqvkfwx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcathtjp.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gt2tracvcpg.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gt2zwvksmyb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bduhvgsd.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gt2jowqhwiv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2rndlzdjq.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2muimtlnb.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2ksoqibin.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2febmeyvm.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2tioztrcs.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acjqlcug.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gt2uvbdcxrc.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gt2yuykglrt.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gt2tozbghxv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2fhdxmpcr.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gt2kejddczr.html


<!-- 参考信息 -->