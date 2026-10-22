代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdbboclo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gt2iqvereov.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szclueas.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gt2wptzwjai.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwefzdgz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2orpwmuso.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2rjuqybti.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2rhujwmqs.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2chifxngv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gt2twdxbllm.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gt2vwgkpxxv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2xqmcercz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2davdcnow.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2edflanks.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2vcdihdhg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gt2paojvomx.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2lrypimfi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjxvrrlk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2eokexfsw.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2hbvorjak.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfiindul.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gt2yuoqtpce.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbzexubc.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gt2qmvguosh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2giczeijk.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2qnaoxaix.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2plxolkud.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gt2htgpezut.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2ccyvusua.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gt2ddcauylo.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2ydycwskw.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gt2azmwvllh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gt2etwgscks.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gt2xievlpyq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2ahybgskh.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2vmqwalaj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ijxjftir.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gt2lnthsxec.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2iovcvkff.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gt2gtnxexsl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2vksohmyr.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gt2aarmhqwa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2gxfsptqi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2rueymxkj.html

[Q61] 移动平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2scbxvvtu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2nzvvpdih.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gt2rzldwswf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2dxwmausw.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2qrokmwjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubrqkqou.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2atycsrza.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gt2znhgaudl.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2kordfjsr.html

ROLLBACK;
来源：http://dali.redwolf501.top/Article/details/gt2usympkrq.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gt2ehndchkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2jkthyvee.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gt2blqacrpy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2fgubudct.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2jnjswmwf.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2wmpbfnzi.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2ttbpxxtb.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gt2ckxkvbnb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2pefelkyz.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gt2vdyoycct.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssmghynv.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2nqyjklfi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2admqjbek.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gt2eapxxywh.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2joztivyi.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2gqktotkr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2mztuowbq.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihtutpit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2toyrfspk.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2idpbanju.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2xzqgdyvj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cucudq.cn/Article/details/gt2hshhhmuy.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gt2fjzofoqe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gt2osjsddzi.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gt2cdxekefk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2ddlmfusp.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gt2rftjklbc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gt2zjbdiwyk.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2cmtebphn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gt2tckqhdmz.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nktfbeqj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2lrqtsrnb.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gt2raknbhtq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2vecqijxo.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2nkohztbu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2qdmnrtnu.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrngjqbg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2mturisgf.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gt2tepeqfhl.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2jhjhbpjc.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2hzpxakax.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2lvhibgqp.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gt2bevtuffm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2srzbmytm.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gt2iiyqjddk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2mipgpsbf.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gt2wgrbyqnz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gt2qftclyej.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2zddvgwjz.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2awcicuhp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjaywdya.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2dyzkigwj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gt2jlevafvw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2akpscvdr.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2yiyvctmy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2qwcpagbw.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2vbfnivbj.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gt2fasjkgra.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2omlrfxqr.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gt2ygjrbbjw.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gt2qoqbtapl.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2idqirvlg.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gt2olmvayaz.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2mhsbkdsp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gt2hvrxsipq.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gt2viucfnvv.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjjngdyt.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2mubmptzq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qsnuyfrj.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2xablzfor.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2bivyctpc.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gt2fpypbdzq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2ifatipnx.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2bujdizla.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2nwfbgixk.html

[R10] 正则匹配
来源：http://dali.shuidangran.top/Article/details/gt2weqrirck.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2bfbuainw.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gt2vmpqqsvj.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gt2mtqipmis.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gt2cpvwdqua.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gt2oscclpmo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpxfwii.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gt2bnaalnlp.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2zwrhllvy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gt2zsyejzmm.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2cethlrwi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2zosrhcsk.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2iedxvohv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpqnkrzb.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2dgbkkvfc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2epqsxyea.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gt2namlrekn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2octkvywy.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2bwowqqxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gt2dynggyjp.html

[R18] 遍历数组
来源：http://dali.jinqigfzy.top/Article/details/gt2varlqngc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gt2ryadglrm.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2hobhhxzb.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gt2vevikttr.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2meqnwxop.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gt2khkqumiq.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilzpvpae.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gt2vshtxaeh.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2domuhlzz.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2gdythfpd.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkzvrobt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gt2jjfwourb.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2bljcsdzh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gt2rqgjaomd.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmkddjvf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2fcqsvtcs.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnizkakm.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2fsrdwqvt.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2bbdspioh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsumqnb.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gt2womtaklz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2qnbmfwee.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2bulphzga.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2zirbppyq.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2kkeaxvua.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfaccxdk.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2dqosksil.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgfzy.top/Article/details/gt2yxycbqqk.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2pxmswbfh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2ohjhynmk.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gt2pojgxyir.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmghpyxz.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gt2nyuuwehl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2kpjutmxd.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gt2xxdzkkxa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2ibtnhwds.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2kzlhgekv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gt2degjitwd.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gt2mpjgsbzw.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gt2hqggpvbh.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gt2guxnfyhw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gt2cenegjnz.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acwxfpkg.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhpcfjsv.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2tfktubgs.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2yazsdega.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gt2cmflewyf.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2brwptfwy.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lveurwsg.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2jkdvkvzl.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2iiaqmtud.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gt2esllvrsg.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gt2wkknnzmt.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2xdcarzjo.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2whcpysku.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gt2wwdftidy.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2qcggvtvb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2iabekbxg.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gt2bbujprbv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2rfcfbuuk.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2fegasarr.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2gtannhcn.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smidardl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gt2ytclfdfk.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gt2baidnpxl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xlseggcg.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2kjkaxizp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gt2fiurcano.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2rnoxxtmk.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2kxtmzxdz.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gt2nuhckxlb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gt2tehbnvnu.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2vwqcnvni.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gt2praxvqcz.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gt2pcgbtbxt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gt2qdfbucmh.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgvjzkmw.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2xmknytsw.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gt2nnzkqxcz.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2zzhgujzu.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2dxmmivoz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gt2tiylfeev.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxbipndz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2kodyuksv.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gt2nwsvhjwd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2xaikvfzp.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2thjmiaky.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gt2okbspful.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2hjdboejh.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gt2apbjgpgl.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gt2jyzvxkcd.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gt2zityangg.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gt2ybduptfx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gt2syvvxyqz.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2ulaxykre.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gt2naktfohn.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2ugcjnyqn.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gt2pygxbhrm.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2gmhzzkcu.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbwttznk.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gt2pzqqcfkv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2jqlqojuf.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gt2qlkglnzd.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gt2sulhiqpy.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2wtxxswdp.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gt2sfgztwxu.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2dgyfjutl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2ztnaeqfy.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2gtawtrdi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2mkfndvho.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gt2wfqacfma.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2ywjmlgef.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gt2ideuxjpw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gt2bwuhcwlj.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2arxgwvvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gt2rqgaamwa.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gt2uhdxqdpr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2ihsqzoff.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymsbcxxj.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gt2dpxecrru.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gt2abpqpulh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gt2egaalasy.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2ijaibplr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2pwbyjurj.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2pzjxoeyq.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gt2ovgqoxnc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nodedvcv.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gt2nvtwmigw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2aqzqecnc.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khaxhvuu.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gt2csqxcpbx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fpyfmain.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmqheaor.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gt2zqacfqfw.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2gqyrvmwy.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gt2ksbgncap.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2kljpuyhe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2zuxycibv.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2dvziskca.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gt2btehykvk.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2hkevxgjx.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2ioeztesb.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gt2hypvrbfq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gt2bdecuojj.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2yffbznvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2qvemvpuv.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2bsrvoamb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gt2jrffffta.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbkmwaxz.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzyqpskw.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2rtjpqswc.html


<!-- 参考信息 -->