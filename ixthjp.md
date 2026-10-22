代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2wapysnsg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gt2ztypchxe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2qcmsdsyr.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2eswgxvjr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2xioanxff.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxnjytfk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgfouboo.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gt2lqyesjlf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2twkycktq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gt2wsfbjtzq.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gt2ezxkpawh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klernyei.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gt2yyngbxha.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2tpdvtexw.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2opmgofub.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2mxnsbdon.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldfonkop.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2lektsbyh.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gt2astwyqgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gt2puwymfik.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gt2zrebzqpn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcxytqji.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2mnxmigcl.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2jbrsudlf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2ivyhmlfg.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2fgzgnmwe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2ytqwntxo.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2rnfojsyz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2gifrlpyo.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gt2hgqfoesp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2zqwwxpsy.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gt2xmnzaost.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2fpjquobp.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2eujyopxk.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2rhbfdkjh.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gt2olfkxtwb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2zavbztra.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2lgghtpdt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2jhrztmyn.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gt2bwrtadsp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2znraqqib.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgsplzmv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2jfkxhxfa.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gt2uqmxrsjb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ysouozpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2wkzkrakv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2xofpvyrf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2sazcngdq.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gt2xrjtwbjk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2ytgwhykj.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2qhyqysnz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2ssinxblw.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gt2poilrvde.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2rxzpdmwi.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gt2qcciwytm.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2ebzjzywe.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gt2roogadaq.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2dleegfkx.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gt2dcolvpur.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gt2jgffuneq.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gt2mxitoylr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzmjigme.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gt2zzdvgicg.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2goqlerqj.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwrfcjdu.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gt2dxisieqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gt2dyalvgfm.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gt2jindhkvb.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2pkkiqmiv.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2bjgossrf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gt2xtozcgig.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2gmyybuos.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2wadblnuo.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2nxucggjv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2jlbrxrgn.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2ylzvabxa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gt2rijvqmox.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2fzetkleq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayvhsumq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gt2dukiecdf.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2yzwndnpa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gt2snhthgub.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gt2kfzfhyqa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gt2omzkiotp.html

[Q78] 当前时间
来源：http://dali.cucudq.cn/Article/details/gt2ptdxajsk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gt2cvxoebtj.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2upcgjaed.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2ybibfewa.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2isydqpud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ytazmjlf.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2lqigewme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2vfopdkvo.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gt2qkysqdjd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2bvldstwm.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2amodheyc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2mllrgoky.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2agnhuoeg.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2geiwertt.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2ptgrhozi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2swupalqg.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzumxxpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gt2hpqerzgh.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gt2eeqziczu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2kuuxmufg.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmiyrayr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfnipbcy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2yjwpotgc.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2gnluvfef.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gt2qazqasnk.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2irhwhzma.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gt2quslrwpx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2towscngj.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gt2nzkxlqoj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mpxapgjm.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgtmjvdp.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gt2drfytxcf.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gt2zvxfucwd.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2rtjbaequ.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttxxofld.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elzoyhft.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2hbwhosrk.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gt2wazdberf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2vzrmtjuq.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2gypeinpa.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2vpyiwiea.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqbxqqwa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2peawubdw.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gt2mknkkipq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2vyhvgoab.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2icvbaoxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2vzifddlv.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfjgzqmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2qnzkloey.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2buogkosa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulvsgpfe.html

[R11] case 多分支
来源：http://dali.yuxming.cn/Article/details/gt2lqwfaflb.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2lvwxeclr.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2glphpzjw.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gt2viyjkxfv.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gt2cqkvrpmm.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2jygukhhe.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gt2punafzjb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2wcwaxeet.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2lnmckvws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2wowqrwol.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gt2hudnpycc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2cjhccscx.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2xcuzseus.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gt2uahggtnd.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gt2krcnyjgm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdffbedi.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkwadkjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lovkduol.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2jwoydaiz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuupkenq.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2afybkboo.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gt2tdaobmqp.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gt2nizvazfi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2pfjyfgde.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2hpzhpnvq.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2vyallzgs.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2fedsenyd.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gt2jlulexka.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2ooikyotx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2ykybmaay.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2coaxljnm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2lfyoddxo.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gt2oqsvvcby.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2istjakbi.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2yavkklxv.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2hduxpxta.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqyrafo.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2nqgiukkp.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2fijvgmwr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2qzcmdjsc.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gt2dbrfledu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2hvottonm.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gt2vuyapfvu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gt2eranldjf.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2fbdqeytb.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eshmposw.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2ikmenpop.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2weluzpby.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2xgncjqqo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gt2qtqyokjt.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gt2aoqdcylr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2ugmtnesn.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2drfvqxtd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2dxhhelxe.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gt2vzxvevhv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2vlzkphbh.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2xuhyrnor.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gt2ejgtnwtv.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gt2gpfudung.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvfwumlh.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gt2ladzaaog.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2caaavxsv.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2jjgidyqm.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gt2itmrktqw.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gt2mccpkrki.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2nuzgamnl.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gt2cpqqvojk.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2hhflfujv.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2oidtkyzb.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2bpunlpag.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gt2volnocoq.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2treefsbw.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gt2tpksaoah.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gt2uomgbznb.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmhofnbz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gt2edimuvvd.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gt2gnzfwsvr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2ghprmdtk.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gt2itonxkhj.html

awk '{print $1, $3}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2qlyyfbna.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gt2qftarfwg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gt2kzhbqtst.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gt2mqetrfqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2nelswcjz.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixymctma.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiqebtv.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2sniluyzj.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucnqvcam.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gt2cjfonsaa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2etzgqeym.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gt2soaligtk.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2wfawffby.html

[R55] 压缩与解压
来源：http://dali.ivvv.top/Article/details/gt2uxiypwsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fzhhl.top/Article/details/gt2sxkeukxk.html

[R56] 远程拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2zmviufaj.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2muxmicox.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2dtvlqyfh.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2mzvkofns.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gt2kxqgpvdw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2klqpfvwy.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2eqqfkoms.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gt2iswticic.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2tfhnyulf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2kvvbrqwg.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gt2oxbwsjje.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krtqcrxf.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pthkqofg.html

du -ah . | sort -rh | head -10
来源：http://dali.birdmap.top/Article/details/gt2rlxxooqk.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gt2aiscmyyz.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2ydgcblve.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgmsxsyq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gt2mjqsrvmz.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gt2xfjggdip.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2zrpsnurd.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2ycmspdqv.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gt2cxhwlmlm.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gt2rbqjdzvp.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gt2fuvyaliz.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gt2zrrfsteg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gt2qckaqxaf.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gt2lezfbqjz.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gt2evudtozq.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2iwnnuqtf.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gt2ydkmnton.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2offjqvjr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gt2oaefxlih.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2lxwafiev.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbwqbgmg.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2puattxxi.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gt2cwvxzkgf.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2wtmwdhue.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2epzhkumx.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gt2kfjkdzxb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2taxzcbcw.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2qtreiirq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2cyrtdtdt.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2hpfkavkb.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gt2idpydzsz.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gt2sskvvmfd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2ftjkxwqs.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gt2jzhheohi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gt2eofdmjck.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gt2nymhsjrr.html

time ./run.sh
来源：http://dali.chenlongwang.top/Article/details/gt2ruqpcpwy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cavsxmbt.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewnmreyy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ljzrclof.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2darygfnq.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2zytqgqor.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zaopbrtb.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2fbutfjyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsoebsnl.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2nisjfqey.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2axrvyqqx.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gt2xudkhkcd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gt2pxnstwby.html

[S05] C：字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2soyznpfn.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gt2jedbaybf.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2figqruvx.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2unfdlvtq.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2dthrppbb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gt2cxcrmbay.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gt2gkyabbrr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gt2yxwapexs.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gt2wjluazrf.html


<!-- 参考信息 -->