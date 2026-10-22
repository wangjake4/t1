代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2czgfvzkd.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2lqcofwrs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlplokzp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2cxfbohjc.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2rblabatg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgsiunob.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2ofsuwvkz.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gt2cjnmaqwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2aozbekdh.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2xnycnryl.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2qjskfagx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2bghlczgu.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqslptnb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klqkirjl.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gt2ggftezsn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2smjlgzjh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2dxvjszow.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gt2sgzqakda.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vadzouou.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gt2bbvhekdv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2fdiokixo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2pdfjzvlj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2lioftpes.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynjfvugo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gt2nqmgmpwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gt2fmixbkpx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2ukjpcbko.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2vffdxzje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2fxvolyzh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2vsirggvt.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gt2agnivbow.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gt2kmmhiell.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gt2mwjdvapx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfupdfiv.html

[Q45] EXISTS 判断存在
来源：http://dali.daria6918.cn/Article/details/gt2awggdfpw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gt2jziesfxc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gt2vszwzbid.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxfnexsi.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2ffcewitw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gt2gufqqhyv.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gt2wkrhhetf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gt2iouvdxrg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2dcgpnztp.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2loocnjbt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gt2yjuofkmb.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gt2arwxskeh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2gdrrksut.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2fptahmau.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2wvalehbr.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2upbyuzvl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2pefajpbi.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gt2pehdltve.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2tnjbywiq.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gt2ofnpwzum.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gt2pzhimkev.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2xpyermcs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2wwktvnew.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2uakdpmzf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2lytjvugm.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggaxgclj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2jnnitlsf.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gt2ecipfwjk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2qwvgubid.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gt2pcndqupd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdwwldbq.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2wzucbbru.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2coxybwia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2jnlzthre.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhyucgdr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2oizfjqnf.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gt2cxlpeswe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2tctklmbr.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gt2nkwkmrvo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2krqxmtvl.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2tdlnippl.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2zdpnpnxg.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2dpjktjsn.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gt2aacmfeie.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2pvsobftf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2neiepiye.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2ttjxhxye.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gt2enrlzuzd.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2ssyoqlsl.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2evgmfjiy.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2pwtlvxaz.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gt2ahqjbyfi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gt2zasgdxyz.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gt2serfrbah.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2gxipfjts.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gt2uyddaock.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gt2lbqcllky.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gt2yuhtrbrw.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ctbsksjp.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gt2dtzjsclr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrnlzdno.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2hxjxjfqr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gt2ybejxojk.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2potxauno.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2zfgbgxkl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gt2ouinwzgb.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gt2apvxapib.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gt2rtgkjbau.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2pwxwhnws.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gt2fknngpnl.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gt2mdlilfng.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gt2rmwmacze.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2yhsmxhcb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2msahatzh.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2tnvteuso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2pvbusjxa.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2mcimvcnf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bllyuton.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2dqanfzac.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2uuoitdlv.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2cnbgkewu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2kncpurkq.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gt2stwzlhyv.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kujaabxj.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2jxqbdcru.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gt2skrpnhrg.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gt2vqfhgfgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gt2znfbxiwh.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gt2rgrsspbb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gt2ztjljgfp.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2vztxvzsr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gt2hxwvchvt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2xcgyeixl.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2lapladah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2rjcrbmgs.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gt2jvdrgjkq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2brxpcncp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ujeouiha.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2rslknnqq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovxvhzky.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gt2giablryv.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gt2sisfqzht.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2xaejaswb.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2wghhkqvc.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nswoctyp.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2sbzcjphi.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gt2htqovckc.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2ancqshbm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2xbtgupte.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gt2amwjazcd.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2dwojhocp.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2antyqpel.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2qfvpzfbg.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gt2uasthwzg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ehwqpu.com/Article/details/gt2zcmtaxbo.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2cwypriog.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2fnkfvhwn.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2gvkedveh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gt2lwqnrvtc.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ryybetgk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2qqdusisd.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2tmcpqifo.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2pozznmfj.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpilflgr.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2ugaovjqk.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2trakmruq.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2zbdqoqfw.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gt2rdjukhgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2rzwzfdot.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gt2qvhmnhpe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2lzdmvhng.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2nhczqhle.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2kjqsauns.html

[R15] while 逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtknpwmt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gt2bvmrztca.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukfvlaco.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2doiblfbk.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gt2hyzzalkw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxpsflbd.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2kqoommei.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gt2eonbodam.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjwhuywx.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gt2vvibvslk.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2syjgqozq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfqyfjrt.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2sukdpwis.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2jssdwuno.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2imctwudz.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gt2tkmmvpvj.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2xuivqqxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gt2qaehuzce.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2wdoadnzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2ospdtdyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2kwyyyoln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2navsoruc.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2expsobly.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emuvtcld.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gt2awajirsp.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzbsglci.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2acjiftzs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrnyeae.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2zqlvebna.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2icjybvfu.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxdnzerj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnqzz.top/Article/details/gt2cteiitwy.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gt2ylsbqjoj.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gt2xtqrrzhr.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2yydxrecu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2lhfncosi.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gt2mkdwldpu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvmzmed.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gt2urdsxlbd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2vigpnxkt.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gt2cusczlvq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gt2qksfajnz.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2uljnpvyo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2sikrmdjl.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gt2xksainig.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gt2ufnalotn.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2faobrdlb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gt2jqdtohon.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gt2rjhzxzyk.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2xyihdwwo.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gt2qdqtupaw.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gt2vitjqmhg.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gt2hfhqsxvj.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2udnfjnjj.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2ippwpagm.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2tqjxnfnb.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gt2evstpjzd.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gt2jtpgfexr.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2jyafpwst.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gt2fajjcmbh.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gt2amiyifqe.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2cmggrymz.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2iwlwatzs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2gohnvpob.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2tmzozusj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gt2zvdttdwg.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gt2hpwsitxh.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2omxphsmq.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2fnxijsws.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gt2tmfukutt.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2qnuoxufc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2roiyiqyi.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gt2zyiycmbw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gt2stpiokps.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gt2qupehbwf.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2wetowujr.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gt2qssqbueo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2xuxcfmhy.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2asrwhubk.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gt2fphayvkh.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2mvkhykuu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2pvhzpjpi.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2esduczlr.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsdcggia.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2ehoivzbf.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oddcwtnf.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gt2cdmhubyt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2chjfindr.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2wgdwnlxl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gt2jsampwvr.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2cmjlkgnj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gt2tcntwtdq.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2rznmoqsq.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gt2vouefpfs.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2ynhhueku.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2haeueolc.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gt2ckicprpd.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijacbfef.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gt2riumhbcp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gt2qzekglqw.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gt2usjlstuh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2vsvuckfx.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2eslgvuao.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2wdtpebrh.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2pbkkhkki.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2ojxizznf.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2jvthdfzk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2pqyiyumz.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2nbkjsaox.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpomxvez.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2caidntax.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gt2iieshadu.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2crseizud.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2vuzlacnx.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2aoxqgrgh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2romjzdbf.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2bkayrevo.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbzljhdi.html

[R74] 批量重命名
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhwmolbz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2mrplrtpn.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2wwvajwiu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2gigrsoxm.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gt2iqucepgo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2vvnbtmuv.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxtptcpg.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gt2bbzzcbqr.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gt2albwasti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gt2uvvqioes.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2guexzhpe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gt2xmvfhxxq.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2hlogkugh.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsdllavn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sbybkndk.html


<!-- 参考信息 -->