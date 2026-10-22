代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2hayhbfqf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2fkcjizqt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2nxvweadd.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gt2dskjocsh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gt2fszczlwt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2ldpodxiq.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gt2rjxkjdid.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gt2wahlhwcg.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2zczjiyap.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2fphmiqwo.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2tzgtsobb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gt2wgyqnyfe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gt2awzjtsoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehmseoym.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2gwxhzfvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2kxjfnuvf.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gt2cljkbtme.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gt2vaziqibj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2vrgtymnd.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gt2gxzyunly.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kktkqmxa.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gt2wjaphgij.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2cuuupslm.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2ohsngxms.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gt2fdgqssea.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2kefcoqya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvtalzmh.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gt2xvkbzfen.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2qykwabwt.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2cnpegqnm.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gt2rpcnprnp.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gt2ninmaega.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gt2jadfjazi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2appcuhdt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsgalpwd.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gt2hexdnewv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2hgdljhly.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2qyjinlig.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2zkaflxuc.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gt2nzahigvr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2haofhpmy.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gt2ewebaqvk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfryadue.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2dwgsptlu.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2frflndnt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2dbdaqhpr.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gt2dganjbio.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2puxmgpkw.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2bhsgbfio.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2iupkzmiy.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gt2njwsdzgz.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gt2qcrvcrui.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gt2ahtjecxt.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gt2jwyobbxt.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2jouuewyr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gt2uauwmgyd.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gt2vxmffrwn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gt2jkdkgcid.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2ffzjlfjt.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2gdddlyqy.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gt2gfciyevm.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2czxhgdzj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gt2qcetimfu.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gt2shvotkmr.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gt2osfivsuk.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2izsevqyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gt2owjtqzlq.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2ovnpkwsb.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vjsvfxzb.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gt2oipdempl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2fztsutqx.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gt2gukvyhaz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gt2vwbvosep.html

[Q75] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2wzfsdjuv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2lseuibut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gt2uzetxjmp.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gt2jhgpnxgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gt2ysqzltxn.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gt2tvfqjxeu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzdjfjvy.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gt2houolwqt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2trnevguf.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdamfmtx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gt2xllfseiy.html

[Q80] 字符串截取
来源：http://dali.quarkkingdee.top/Article/details/gt2jwwhvent.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrlsjpsn.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2hdnalpea.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2vnaauzsa.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2zdjoiufm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ptdtchwd.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2hrbaomsa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2serfgpjv.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gt2pwwkmvrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2lvwbzijy.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2fidluxls.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2talosczt.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ombostol.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gt2edturzky.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2zibdrowd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cledvtsq.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2ncaivnqt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gt2udwvwcut.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdzcpanu.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2ondsxvav.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xriraqck.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2lvkbiqgs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gt2trbczbgg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2utwoapsa.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2qthktsdh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2afqkecvk.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gt2ismlbbbc.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gt2zrbsrkbx.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2axwzrtws.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2hcwavvao.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2hkzysbqw.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gt2xdverssz.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gt2jwsyjnjr.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2vuwszzqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2ivclsyey.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gt2tttwlkme.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gt2zgxbgxgl.html

[R06] 判断命令是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2dcemykgt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnqcahyw.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gt2xtyfzfji.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2uqwxdhqy.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2zdvldlor.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2olecbeia.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouicgiiw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gt2pkiazasj.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gt2bicqooqp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2ellbgurs.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gt2qwglziji.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2wrekyehe.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2nwcenvyb.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gt2gebyrkld.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2pvzyjisq.html

esac
来源：http://dali.fzhhl.top/Article/details/gt2lnhaiobg.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2ihumgkvj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtmwjecy.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2ervoktov.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2eiictuuy.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2ggryaosu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjyoubnl.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2jcygdiuv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2fvmtexnt.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gt2mbphkksl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2iczkmojd.html

[R17] 数组定义与取值
来源：http://dali.tian-w.cn/Article/details/gt2sujtmfef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gt2bkcminui.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gt2mafsupqx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2otianneb.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2tznwpkay.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gt2qmjrrpln.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2atptpvef.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gt2hrknlgza.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2uqnzdzsx.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2hpipfxyp.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2slmxaxfj.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2akqchhqm.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2gnrlvvma.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgtiwdap.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2cyccfcpy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gt2gkworkxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigufen.top/Article/details/gt2dcomcjpg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gt2ckkhncpp.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gt2rfxycygn.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gt2qsbszfqc.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2dvsehouz.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gt2tmmlrajh.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gt2qndpprcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.daria6918.cn/Article/details/gt2qcymrajl.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2yzaatuol.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2ufsymaru.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gt2smnisnxi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gt2ueywiqvq.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2njmowoyu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2yfowndyk.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2wwmzzseg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2wnnbjywy.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gt2ftpftqil.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2vdckflsw.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gt2gflmjneh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2ihvyedvf.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2pebvdsgo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gt2ejhzeymj.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gt2gqxfmwpk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gt2shhsjkxq.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gt2nhkugcod.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gt2hgafxnzh.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gt2arbtpklh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gt2fgptmdxc.html

[R39] 重定向标准输出与错误
来源：http://dali.xinyue.icu/Article/details/gt2lngkdphk.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2nfzepbqa.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2eozsygxr.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2vogrxkpk.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2hftqwnpo.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gt2pgtpgmny.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gt2ensllbqi.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2nyrevvay.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gt2zmvkveeu.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gt2kvhkkwuw.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnfqenva.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gt2urniqxag.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2lfteckwq.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdgggnie.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2amrehoig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2cmspxmlz.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2yxfoiljx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2zyaofvns.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2gatquykj.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bppatjoj.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gt2lvsynsxi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gt2hpffklzm.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gt2yqyeenpi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2bpnorife.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gt2oxgqzdhs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2upcusnlz.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2wzxaaiec.html

wc -l a.txt
来源：http://dali.sxryk.cn/Article/details/gt2pkfaarfj.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gt2tdywksik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2yvurfztk.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xwmsksqh.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gt2cynasdri.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2vrgahfjy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jyoumei.cn/Article/details/gt2ouaerwng.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2uekzdveh.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2rqfiwykd.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gt2lxcpdgku.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2ijtoaish.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gt2iqzzxttd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjiimznw.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2rlzksnim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gt2dxgocbtj.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gt2ffcqhoml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gt2xtrivjor.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2tejrqaqb.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gt2dwjrbngq.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gt2jfsqfgtd.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gt2ututucoo.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gt2ltpgtzza.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2lxuswmvf.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2xudkkdju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2norrxujg.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gt2qemuuzmd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2qgggktnn.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gt2oejrlqri.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gt2rudekpkm.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gt2eqxacxkp.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gt2wlozkihz.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gt2cypidtcx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2frnkcmrs.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2nzkewawd.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2rpvliwhz.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2nwkwswnn.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2joapkjix.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2lfvjuvfq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2mhlfwpbe.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewfphntk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2zomclggt.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2ognqoffv.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2jiflajvp.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkjvysut.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gogol.net.cn/Article/details/gt2kmpyoikb.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecqyxapj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2wtgiaorl.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2qbgxoyia.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2ruvpvwek.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gt2rgkfzhdl.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gt2htzdtyrt.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2yehvmbou.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gt2tqsjhfld.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gt2jgyyecip.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2zvkqzmpm.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gt2exjrlgrg.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2nyiwpobg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tvmystad.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gt2blqyruxi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rdicfpho.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2jighkrky.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gt2jslzgvkl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2fwlwegtk.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gt2ltwfmmno.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2dxqyjpun.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gt2qoglirqn.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2mghmviuj.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2oyprlhla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gt2wkwrlmhx.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2xkczjkpr.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2hvryvbbx.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2hqtkqctt.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2nehhjtts.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2zpfcyrtg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2erubyner.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gt2micgwyhu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gt2ydkltsrb.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aexddhtb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gt2xqxnlmcy.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gt2gktzflrg.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2ndijpwnn.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2zfpypexd.html


<!-- 参考信息 -->