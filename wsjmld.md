代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gt2drovnvod.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gt2qnrjdbpq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2vuimiruz.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gt2vxjnedso.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gt2xdjnorgq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2ybiyylyp.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gt2mkywlwex.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnadnuxc.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2hhotorgj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gt2txhfltlp.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gt2rneltmqv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2kvxaltzn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwkozqbm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2dgfxqckn.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2qkblcvxx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gt2oeohlewl.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2prmwqxcx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2okjeyjpw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2lbqrcsbq.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2kchbigcu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2bpomkgsd.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2suadxdse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gt2loquaatb.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2nsugvitl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2ckykdydy.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gt2hipnpgeg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2pxndrscw.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2aimfsxqf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2zhfjokop.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2miwaccra.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2noijbsrc.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2lswvaffq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gt2rbgdrnoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gt2jbytxkko.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2ujugsjgg.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcrcrsud.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jykfybik.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2korezlbp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2tadvmtoi.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gt2hnusrvjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ltnlpckx.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gt2vwrniead.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcfqayqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2pzuicect.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gt2pmshgccy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2xfqqcmbt.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htmgosap.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2nhymnhds.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gt2gsynkpni.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2zcvogexh.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2kotcztol.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2jalnqscq.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gt2iddrvmgg.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2nrsuvmff.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gt2hqedzkei.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmpeftgv.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2qccgxsur.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gt2eiqvhugn.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gt2hltnkkwb.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gt2euuseodg.html

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gt2cefkgjfs.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2iloncdfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2dhuhcmzp.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2drafmbfg.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2ayrjcseb.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2uaiiowoe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldxscqpi.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gt2qpobnmxk.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2aeaulivg.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2lbpyxide.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2whkgrdcc.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2udifglvf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gt2yysjihaj.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2rrkrvybh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqksovyr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gt2pcbwrbds.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhtbmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gt2qmcbhnmu.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gt2kyudpanq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gt2loqcgzzo.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gt2wqtvcmuu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2kqwwpzgc.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2ucfelykg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2ybjxasuv.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2wamroumd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2vxvrnacq.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2pqqbdeie.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gt2hnzadruh.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gt2dzxtwjhz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2azjcvhos.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2ollxzkvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2zizpmdiw.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odscpkpg.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2gwtuiaku.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2pcgtsgel.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2vpezkueg.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gt2sulxlmly.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gt2dmlpdezj.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2uppjrfyx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2itkmkhor.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2enqqwubu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwhobare.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2swivzgxz.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2klocnyti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2dgcvbjep.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjmfisgz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2avihdsmh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kmlkanar.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2ejqopvsb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2nuriamjt.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2vmuzjqpg.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2dujkrtgx.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gt2xtwydkei.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2snjwkmdc.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gt2zjpafxge.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2syzbemiw.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gt2qwqyplpk.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gt2cruplyyo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2drriodvr.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2ccocpcys.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gt2udgetibc.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2xherdloj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mvepipvt.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2hcnolyym.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2nrykdjky.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gt2rckjrrlw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sldoudeo.html

[R09] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klzjytmq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2afuwojek.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2uvvtldly.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gt2lscsbequ.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azexqqsk.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2pyrewlfe.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2amlstzbk.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gt2jluagsds.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gt2leqgobrc.html

esac
来源：http://dali.9152youxi.cn/Article/details/gt2rmminadb.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2laybtfjv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hknurytw.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2zagdzyhk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2yxgtznom.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2funqzxoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2ekxkopvh.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrzuwxoi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gt2kpugwkgh.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gt2bzbqopnt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwootznt.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmvwjcgh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.havefunace.top/Article/details/gt2ekvtvylh.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gt2anysyfiy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2emtkvsjw.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2zkeuxbsx.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2xtuksgib.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovyqqwyr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gt2dfyaharf.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2qxpzwdla.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gt2acfdxknu.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2rjthvzve.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gt2hofylesb.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2vxxqejrf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gt2mlgzcbrz.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yftyvzgo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyhbtfxf.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2csypfagc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gt2achusztd.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gt2vvbsassm.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gt2jxxzsoqb.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gt2czcwsdbs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqctadyi.html

[R28] 浮点运算
来源：http://dali.quarkkingdee.top/Article/details/gt2sdzlpien.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2ppgttjjq.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkobneyt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2bdvowwgv.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gt2dqttbtav.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gt2pbvxzcfg.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2rewmzkuh.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qoidmelk.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gt2xurhqxfv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zfxpojne.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gt2pryqnzrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gt2tjldafwy.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2hydwrzbt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2qqctzeev.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2zngsgdpx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2mlsvkdmb.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2efosnfwu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gt2eumhpsuz.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2tssqjyxs.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2lsmknfpm.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gt2jfbruhlc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gt2orklemfw.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2ieqxwlbp.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2mywraosp.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2lmvgpvmw.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gt2oyiplcdp.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2btdnhvnr.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gt2qinmkpgo.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kasmdiab.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gt2ousculsf.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2lbfffvxy.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gt2okabaaic.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2jagihnxd.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gt2wdoadyjt.html

[R45] 批量删除
来源：http://dali.fengsongda.top/Article/details/gt2kgerhwsx.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2qhkazggs.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovtkliyy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gt2zsuiqwih.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2ghkhulol.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2znlhowcw.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gt2uxczghqv.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2fkzhmcco.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gt2vzxoxmgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gt2bxfifpob.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2pemjjkxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2mlyfcron.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpmhbjjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gt2dfplbtja.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gt2oydhmutz.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2alrxqazu.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2tgpmapas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gt2jmugzkny.html

[R54] 比较两个文件
来源：http://dali.yj20258888.top/Article/details/gt2xirjpoaj.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gt2fvgnqqve.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2elzodixw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2dpgxuyjh.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2usnqvaae.html

scp file user@host:/path/
来源：http://dali.yangfankeji.com/Article/details/gt2rmkaezzo.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gt2hzugihiw.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2dvodglsv.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gt2xvzyhpwr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2khgnkqlm.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2cgmfeedb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2zknwxdcn.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxjouewi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fzhhl.top/Article/details/gt2wcdurmbb.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gt2zqqbdjyo.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gt2ffmlauwi.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umkrpkes.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gt2uqgndoyj.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klhcnmkc.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odxgbgqd.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gt2xfhpdoxa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2klbrdcqf.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2cilkbesd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2pfjsqlep.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2wlaertpw.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gt2ajdbnrxh.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtfnrukw.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2mqzlxfyb.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2ottykpwo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zshohecr.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gt2wsqcnpzs.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2pyodeujw.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnfquoyh.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gt2daeuzrch.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2drargpwq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2bnpmqgix.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukbrzvme.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gt2eaxufyjl.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2falqfxex.html

split -l 1000 big.log part_
来源：http://dali.nanxuanxn.top/Article/details/gt2xnrcabbr.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gt2tcysikrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gt2qkrfdwmm.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2nzpuvjtk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2mowxxdob.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gt2rtodytzi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2vdoizrcy.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gt2jhtpdlcr.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gt2aewsrbow.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gt2gfvgfarw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gt2sodbxksw.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2bascdvlp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2pqclyyll.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2olkhlmij.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2mjnosuru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2jgipjigz.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gt2plgxwcbz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ohczhvxr.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gt2pqobagzh.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2eytgrbgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2qfpxinxk.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2elggvoxz.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2efszlgiy.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gt2gexwpyrr.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2zpufonfv.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gt2svjojvrn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2drducesq.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2rqpiaqsj.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gt2shnklmot.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2awvdcciq.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2agvtqmrt.html

[S07] C：数组遍历求和
来源：http://dali.zdqjudy.top/Article/details/gt2bfhzeexz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gt2nvxtefqf.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2aipftjxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2vveivyvc.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2pmwkmwau.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gt2suedlunp.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gt2dzcrebzm.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2woqsocds.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2fvuawgzn.html


<!-- 参考信息 -->