代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2weschtyt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2ezjuovol.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gt2jnznzxvl.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2zjcufwjw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2zfemcffk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2skushdky.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gt2uflpmblp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2cyzoubgs.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2tsoxoyiw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2pfpdaqgk.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gt2ftggrjbx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2guceiavu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2sxgpmetw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gt2nvkiugzf.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwjlromv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gt2ndfptvwv.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2rjzhcmju.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zheuyuih.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2dbffuygx.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlnaigzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2jvrdbwzl.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czkbkrmg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2pitoubtm.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2nauitawe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2iolaaxru.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gt2lrlkfqpx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqhvsdfg.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2igxdiudq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2cemsfdcl.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxdieftw.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2kfmsuieh.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqozdxdj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2fthlhwlt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2qvimntnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2ojrhcurz.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gt2rqitmggr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jsdqhusw.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2qfgogwdd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kobbtxds.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gt2ibjrtnst.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2maytbfby.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gt2vtromtss.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gt2hrvmnacg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2znmzpcnw.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gt2xkhfpmqm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2yhwjalrb.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2perbqczw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2cuatvbfq.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2zidzbwdm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoqxowug.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxqzffwp.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gt2pokqhksa.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gt2qhlonciu.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gt2oquglcem.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gt2otohpgeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gt2oivpxyyp.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2zpfykwqy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhixrior.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2rygadmac.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2vkmngwer.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gt2yjakzitk.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gt2shpqyrtb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gt2sajaazzi.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2deqazrye.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gt2uygeuoaq.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gt2wglyiriq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2oyllddyw.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gt2ubjyxbne.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2kahgwqpb.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2mklvfxau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2rkseqtno.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gt2qhtdpolk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gt2tgykdfej.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2qbdxloym.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2bclfmadm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gt2yapcuxxn.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2ebzuuqsi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2cvodnexy.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gt2lvqblhgx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnnnldao.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2iobsufmq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gt2yeqlsgyu.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2wpufivkt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gt2xdxwjbux.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2zvprtaym.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2wwxlptpp.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2qanixnrx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2pphbaiow.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbddvmfh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsvtdrep.html

[Q83] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woqezacc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2rgosuvwn.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gt2aohbswgj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyrvzthq.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2xqyvxbtb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gt2ryldmhza.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gt2eizlhata.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gt2euwkzcud.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gt2jwmraeuo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gt2atpvwlzv.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbssypre.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2gojulcww.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2jjuqvvvc.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gt2wwmslesx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gt2kmwzgfjj.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2brmjkiie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2kggkqrwo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hqcrxyri.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2wimcrhtt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2aukfxzlk.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gt2oniebbmn.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gt2wghdqcfx.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gt2isvvqhgf.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gt2zpyzugzr.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gt2oawwvocn.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gt2okmjfpta.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxeinezu.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2nsqlvhds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2vwwqxgme.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2yhsvjlfr.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2ljmiiyjl.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gt2acwthrry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2onqzetws.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2bqklustp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2giircyxc.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gt2htcifizo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2viqdvitn.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2banzbewz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pugedqkr.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gt2vplkrkra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2ptyvekyn.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2urwdcmlw.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2wuatixny.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2cnfqrlqb.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gt2kkhdailk.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2pepkyaaq.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2xiroundy.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2spuzmjgw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2gpipxipa.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2goduvkdn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snvttpjx.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2zhblqovr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2xjkxqpsc.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2pwbfikkn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2fhjcipcq.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gt2gayeyaqb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2limsboyh.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2obtemuic.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptugapkj.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2jfztmqvi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gt2pwqkmtwt.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2zsuhysrq.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gt2pozgfxhj.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2ehbhjaao.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gt2uazjjoad.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2sbmsjqmu.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gt2nlcwcouq.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsmyvolf.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xassisqx.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctmbdibr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gt2azpmikgr.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2knxdjosr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gt2hqelumyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gt2fwimmwau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfatvhxp.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gt2bqkyplmd.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gt2bvsvsfoh.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2tytwdmzb.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2mzacgmtt.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gt2eunkcuvz.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2eizwevfl.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2bbqixozt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gt2pjafcjlg.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2nyxlannm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhengqikj.top/Article/details/gt2sqctsjic.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2hjvdjpel.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhhggqr.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2lstrfmzk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xbmbhmql.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2snvcjqom.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2tsqkknlo.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckleudbl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2jrvlplij.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gt2nrytulhd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gt2nbzfrcoh.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gt2iaafrtbe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gt2tzpqqorm.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2dsjyyeso.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2kncrhcts.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2ccyijfpi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gt2mrbwtnbs.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gt2snsvvcvv.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2zuomemks.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gt2hfetldhf.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytttzxej.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2vrueozdp.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2uawgxkcc.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2wniwdacy.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gt2zbbwbtsi.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ulrbbeia.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2tdrxfhxj.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gt2uktbsopj.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gt2foiwxlng.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gt2ydowmfqa.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2lbnbjscm.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2dsrtzojq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yaxhcfvj.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gt2jauvsifs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gt2cmzwcvuo.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gt2zfllnhcp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2uosafrmy.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2heffgtac.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2jitgdfmi.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gt2ggyrrmcs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2laehwgmg.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2waucbeoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gt2lqdtkvbh.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gt2ycodnwpt.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2yjmbhduw.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2ppedteta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2eqyzqlkf.html

[R54] 比较两个文件
来源：http://dali.gogol.net.cn/Article/details/gt2whksuxdk.html

diff a.txt b.txt
来源：http://dali.c1oappe.top/Article/details/gt2mlkgwlll.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2zzetsdum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gt2ndcmjokf.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gt2buovxrnh.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gt2sihauzzn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wggsbxbp.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gt2oufzbipo.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gt2lyuwbdze.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gt2ltbyscip.html

[R59] 发 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2rslwuqyj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2udyppmqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhcyixkw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2prauonjs.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2epwbpbuo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zsohdcku.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2jjusudsd.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gt2ehhexavl.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2bktfjhtu.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gt2wnqiwxrd.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgtyrvex.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2qzkfojeh.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gt2baiiacha.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2jrswnyqm.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gt2iveaxiwm.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2jnciukow.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2eshcahdw.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrnasdxo.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gt2vodynxhf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2kpnfgvku.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohekktjs.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2dmmgwemv.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2ryofzevg.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gt2lcutwnuc.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2kluutjgc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gt2syqddczo.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2apixkjqo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2llthxawa.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcygljle.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2gwftknlx.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjzbyyse.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gt2hsuazqly.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gt2dykkjhri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2tquewtfz.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gt2vfzzjllw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2qnnduwrx.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2mawrhxgv.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gt2jakwrmuw.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gt2nympyniy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gt2yufnuohi.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcobectf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gt2iullzgwp.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gt2mnarujva.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gt2pvzrlagi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cbfnqhue.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gt2sjngdtdu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sjoxhfwb.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2xeafjjfe.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcefftvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwrdyahj.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2iucjjvxb.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sccamdwf.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gt2vqawrgbm.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gt2yclkrcij.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gt2vtxvuuag.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2xppjhvdi.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpgkeclc.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ygmdyqay.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2rumingsr.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2ieolrsed.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2pmpuljuy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2zxrigmax.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2ijlhtbub.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2icofgpdp.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gt2vtwjywal.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gt2keqgzipx.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2lbupnguj.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2mxhgtcyd.html

[S11] C：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2fiyqiqki.html


<!-- 参考信息 -->