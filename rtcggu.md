代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gt2rgjmgttj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2oezkzfor.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gt2wxxzjqyh.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2xlbkdesx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gt2qxfijvdn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gt2vzaawrvj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gt2hearysrp.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2szjuchee.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gt2wlpxdioy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2zgkjubrg.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2ygdhswzj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gt2osdblmny.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmvhbzce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gt2fpoqagij.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvvmgryr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2ognknzor.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gt2ogzuaoyl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2yxjsvjln.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gt2jnprovom.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gt2bryjndhy.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2yahzzyof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2bxoqiwdt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2erbspsgf.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gt2mimykcos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2mryflqpp.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2bkkrhwex.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gt2kfdopwpt.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2eemagsvz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2upsvygwz.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2ovgwmgdt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2lyylbkgi.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gt2tppnibge.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2vncyqsyv.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpslcdwt.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eugayzhg.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gt2kdstucqt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2namdmmsz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gt2jejpqrog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2fxcofzod.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gt2uzfzgjsh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2xiwgrbsl.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbwvcali.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2ifcaznci.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gt2zosgobxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2qiqqvybo.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gt2oehesxol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gt2ueqlxraw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2chrybcva.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gt2gtzufjds.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2lxqgsesr.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gt2udwoynrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2saigagzl.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gt2ehfuvkem.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gt2zkxpstcs.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gt2mqvjipxw.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2pqjbfzmq.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2qefnfxpo.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gt2rizacvpt.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gt2pgqeacqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2dcholvol.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gt2iprkzmoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrkvhlxd.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gt2tdtaxegi.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2vqejuwqm.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gt2kbxswckc.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwvxfcac.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taloypqq.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gt2aewjjvft.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2lhbfsgoi.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gt2yeiabexm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gt2ywngjbkw.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2spdjmfbt.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxfccwuv.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2blqqbqyo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gt2zfynnjof.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gt2kyeefeyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gt2barvqije.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2ltdamdeo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ybyixjpu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2pcokhbmn.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2wieqpkie.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpdyeqxs.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2ckoegajn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgiofvuy.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2iuubtkcv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2kxwmibve.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2hwkxuzim.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gt2cavtcxcm.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gt2olxieple.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2pxyargqx.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2jejvrpcs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ripdddhz.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2bgvroubo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2lbajxrle.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2rpyuugbm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ffwujomp.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxwjueem.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2mvbbjgag.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkddroxb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gt2yqgttzze.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gt2dfwpfrzk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2blaeyegj.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gt2xzfohrib.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2hznoxbxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2abyvnajx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gt2flrnhbff.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ztbfhvhu.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2ulqxfawd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osmenttb.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfcxtsnv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gt2gjmbfrgf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xikbklod.html

R. Bash 专题
来源：http://dali.jianghu66.top/Article/details/gt2asgmoxle.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lwxvlzrc.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2worlnwvz.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2ddrztucc.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gt2tvapiiww.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gt2ridwlbkj.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gt2ctlnojfe.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmyetelw.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gt2powfjzig.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gt2bgcmuyzm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gt2gojikbun.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2vzzrlqri.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2hwyygtsp.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gt2bhcylqdx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2lrqyvaya.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gt2nbluxufg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gt2buucvtro.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gt2zlpapzkv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2rxatcipf.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2zgkdpann.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gt2rgzbhara.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gt2cfkfchoy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2vgpgotxz.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2vjpvaqds.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gt2mabjjtls.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gt2xpbzyyyk.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2wqclnrfa.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gt2vgdqdvdn.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2jfwaovow.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2bamhacfk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2unqsugtb.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2odxwolpr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2mfooohii.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2azvugsgu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2efdotldr.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2lfiosood.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrbmhici.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2opfekyfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2uhzlzrwn.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gt2rseeyylz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gt2lbhnqupz.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gt2bibgdudx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btmzyhzm.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gt2qhombwoa.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2cokmagkd.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyzfbcpk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gt2xobgdvqj.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2shknjveg.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2fioezwgv.html

[R22] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gt2vyqqhvdl.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnjblbtv.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2bcloiqfi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2uzbvyexn.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2mebtenzt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2jqnwafqx.html

[R25] 去后缀 / 去前缀
来源：http://dali.sxryk.cn/Article/details/gt2cgdbhcor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.quarkkingdee.top/Article/details/gt2ebkufqae.html

[R26] 命令替换
来源：http://dali.cheryme.top/Article/details/gt2eobdefwi.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2ahjdyrwv.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gt2gzmmejfu.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2zfynfnuu.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2xfjavsmp.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gt2gdjfetlu.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gt2jfitmzbr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gt2isldlrcm.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2lfyfhepg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgqkuqxq.html

[R31] 局部变量
来源：http://dali.zhengqikj.top/Article/details/gt2zbkbbqbz.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2bccgbbot.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zficddcu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2rkdztdbx.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gt2qtizjtxc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gt2ivsfrhug.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gt2jmyjicdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2zktmyrgq.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gt2ywdejpld.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2ffqmxcdp.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2mfqiltsn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2blrlcllb.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gt2ggteobfx.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vunjfwyz.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ospmpicg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzpbgous.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gt2kaedlypo.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2bvnivvti.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gt2mqcyylaq.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2ueoigpqw.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsqchlzq.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2ctbnbfke.html

[R42] 输入重定向
来源：http://dali.xylfe.cn/Article/details/gt2njohmjqr.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2slpcgoyx.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2ihqbngzf.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvgxmqwz.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmcmkihg.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2qoyarsnm.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2pnrtedoe.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gt2pkvfimre.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gt2vhafpdnz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2yfnlcuuy.html

[R47] sed 单行替换
来源：http://dali.sysykeji.top/Article/details/gt2jgicwoes.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2ggrpkipp.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2gmhhtgls.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2vffoaotf.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gt2awhdnwyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gt2mrdmvujf.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gt2mdhkqjyo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2xgsazrnb.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gt2sanoqccm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gt2fxthdhsy.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gt2evetejip.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2sfpuqgfs.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gt2jypagjaq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnxiangtu.top/Article/details/gt2jarhqcrx.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iflskfou.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gt2ntzprwws.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gt2jylvywhr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gt2ffgslegh.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzluzchm.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gt2xdxnwoac.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gt2opppzgjq.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gt2dyperotm.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gt2dwgusosa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gt2uhdivozg.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2apxardve.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2vdnmwuwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2wlhxtcxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2fldbouvx.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlijhipi.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gt2vofroifz.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2znhenifx.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2njxcyqhs.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gt2eqbbdwrm.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gt2paruscoc.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2mrqvkbgj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2fxeqpqbd.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2ibsdoeol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gt2juvnuvuh.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gt2gukinrax.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gt2yjcicsje.html

[R67] 生成随机十六进制串
来源：http://dali.gogol.net.cn/Article/details/gt2qqwonrjn.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gt2qkqnmznv.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2tjcyogqk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gt2yajjcnks.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gt2hnodwmdi.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gt2hezgmzbp.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gt2lkhucmua.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gt2fcvfgwmd.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2urynrkgo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gt2hplddial.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gt2joehqobn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2juxnblml.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gt2abxemihu.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gt2cbptasrn.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gt2knkmtpve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gt2jlbdiojx.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2vtjxtaxc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gt2lbkhgyxq.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2zlhdnqzq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2lfwfsopm.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxenhmne.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2tzexjctb.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2wrvwjdhc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2dygnyaup.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjrnomgv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2zwdwstlw.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gt2fklbrlxo.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gt2httfddhs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2remmojjs.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2tiyvlxtk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zrkzxaat.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwwxkxey.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gt2sbwuegdf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2zozyyzee.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gt2kbcajasw.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gt2jwhxbevu.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxwhrdvp.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2ujqxqodh.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2cuwrahaa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2iqlnhxgd.html

[S05] C：字符串长度
来源：http://dali.yj202588.top/Article/details/gt2dycuyhlk.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mvdnwrzw.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2ouhsilva.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gt2mbbvgpjp.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2rhweqvga.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2lnqkmdpo.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2jykajvxj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xldlmnsx.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gt2yzcvgjsg.html


<!-- 参考信息 -->