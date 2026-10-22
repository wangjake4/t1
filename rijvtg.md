代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gt2yrznptyn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rovpacdg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jslwhocs.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gt2ernlwyns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2eomtgfrp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2omsqdanb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gt2bqzrlrzi.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gt2xhleioii.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2tsnfczxu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2exqqjqdx.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2bjskdeos.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2xbmimaok.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gt2kbhgcnwj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gt2ecofebex.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gt2slaeemuq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gt2kysmmtzy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gt2dieagnkv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgwnyole.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2cbwwksun.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2ztfpwajq.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2euncqmgu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gt2iolwvujf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gt2sedjblum.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gt2dqdannrw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2slqcfofs.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2jleybufs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2gkbxwmri.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2tobooivl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gt2uhanqqrt.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2yrwnzead.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2pduqugpu.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcbpugzr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2gspeilcp.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gt2gjsaacpa.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gt2mvbqvhqb.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gt2uuxmlhki.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2gptfrjdw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2lshnddlf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2zlbcqcet.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2bhtfajrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2jnkjodpf.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gt2ruiflxul.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2mudapmtn.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gt2vbgcitlf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2wcylanfh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2wiyrdjdz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2zfeqatvq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2kudknvkb.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2pmflnzrg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2brvmjkzs.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gt2veqywucw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2idgadvay.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gt2gpgfzoey.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2azphoddy.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2savocaoa.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2rjlifjhl.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gt2tgujjkzp.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gt2bibufjan.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gt2gmjizpqi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gt2icefkrzc.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gt2itrzmrey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gt2ggnekgox.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2dwamxyjj.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2dqczvkei.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2ikxggdob.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gt2opjzzrvs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gt2pvuctmau.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gt2qxuwuwcu.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2qhrxrbxw.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gt2ezegifub.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2lbsgjxwo.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2vzqgzqzq.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2wbgnwgqj.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gt2waegzxig.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkgylupo.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gt2keupxrzu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2yzyfrmue.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2vlkznzlf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2tshknwwf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gt2itufmenb.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gt2qtrjghzt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gt2ftyvvrmu.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gt2jdbznump.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2suodncfe.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2mqyrflfj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2ysmxrbtr.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2dvplsund.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2qdplbjgy.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gt2bszzjhtb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2eevldlip.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2bcekaeaw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bggciowq.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gt2wgogolvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2mxknaofk.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2zvpkbjzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2arbgjzaw.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfcpclls.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2mvquxztq.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2heopmeln.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gt2ubrettuv.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gt2tuldhjlv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwxduwle.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2isswgpts.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2khoqzozf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2aldrwnmx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gt2ntcacgsw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2wrxiynbg.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gt2ryikcgwc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gt2kpljouai.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gt2dneramky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gt2cfhgbaoo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2acginpwz.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2ziogneum.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jmhdyarh.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2etwcgbrh.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gt2grttdroe.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2ihfloeju.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2moenegjs.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gt2ukfdevaj.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gt2oejofguv.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gt2yqnhzcsp.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gt2abgqvgml.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gt2pfkpmqwa.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gt2sxfmmwbu.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gt2brbcakdz.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2dezbyegc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2jcwstobo.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gt2uyeihegc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2sfrcicua.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gt2bmrgvytp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2qbdiqwbq.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gt2ykfdyumc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2asxlzlul.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2jhttepea.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcsquwvb.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2cpfvocmi.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2koidedwy.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjhlbqxl.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2upccgnws.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2teuryabz.html

esac
来源：http://dali.tian-w.cn/Article/details/gt2hiytxfwy.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gt2abwjyarn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2trfezerz.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2drovhnal.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2lntqhern.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gt2wefceuei.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2kpupixze.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2uhwljvnc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2klhnsvnq.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2zyhtphgf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2fhuzflxf.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2hfifqana.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gt2jeqzjxyg.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gt2pnyoxjaw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gt2jrcxptzb.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtxanxer.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2rctmgpge.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gt2ysvqmdkx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2txtbhufg.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2smggytdp.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2dbushypd.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2enaifuaq.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gt2bdgxrfhe.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2btmjgphx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gt2uydxryqf.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2hkohsird.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2bjvsrooz.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gt2hdzbewpa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2pzsattbu.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gt2digyxryn.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2luivowle.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gt2honpcvre.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gt2ohowzbvb.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2ezlzhlgb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2eqbcuzkb.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2uiusklmh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2sbxrhxki.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gt2afpcvbgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2vwivfdmx.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2rebpfdfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gt2mmefcozp.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gt2lysvzqck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2ulcicsfb.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2fgzzmivw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gt2pjvctimk.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gt2iuhnxlqf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2fdldugtb.html

[R35] 后台执行并等待
来源：http://dali.fzhhl.top/Article/details/gt2mlwaxpet.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gt2bknoyrzy.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgxrpech.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2wfzgramb.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2eaquipcd.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gt2rfliffoq.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhtjtwxj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xinyue.icu/Article/details/gt2fmlgkdag.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2jsghzqxv.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrjkrpfz.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gt2xkbomgvc.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2yuqqgyxu.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2odmalqay.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2sjhjvzva.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gt2tlekuxrd.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2kxirepdw.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gt2tlulyndr.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2tuorpjen.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2bofkpfyb.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnujcsbs.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2yyupccrk.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gt2nnlorjxe.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gt2urukqmae.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2imftryvq.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gt2ykwliuwm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2teimtejw.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2whbsphpe.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2fxtiykfq.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gt2scrukvsq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2qbhwunoc.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2istajfeh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gt2oiibbnle.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qutnteta.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2ybpaextz.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2lonzdgnr.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbngniwi.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtfncckh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxffoclz.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2dlsdzqog.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gt2mvychgff.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gt2mkqjldiw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2eobktkef.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2upvxztcw.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gt2zeglqrbg.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gt2dtlyvyaa.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gt2nioewask.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwwlzpjv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2ubnyhpcm.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2lvwinclg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gt2xgonamov.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2yozfibne.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2wxdlcqcn.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2depmtpxh.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gt2pouugqte.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gt2opdmksed.html

du -ah . | sort -rh | head -10
来源：http://dali.kuanghao11.cn/Article/details/gt2uojahdrk.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjafrrvs.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gt2rstmqnom.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2olnovitj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gt2tkpowdec.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gt2onmklsca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gt2nhriufok.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2jyykfwoy.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gt2dcojbcyz.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gt2esfmgfhv.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gt2wkrypfct.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gt2aqxpusvw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2pxputwdf.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2uzvyrbei.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gt2dpjhpksl.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueoxqkdt.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2uwuqmglg.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2ybwsozxs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nskygvym.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gt2qwctjmpl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2hbswccdf.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gt2tfofjknz.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gt2bvbvplkm.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gt2wyeldxmp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2bdrtpkda.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2wpsowbga.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2babdviyc.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gt2msqrsyev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2jimlovrj.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2qfjfusim.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gt2pggprkxa.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gt2ifqzkasx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2ufwmasna.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2pzufbszg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gt2sivaggcs.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gt2ajtmgjpp.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gt2zjwkzjog.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ovftftgf.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2gdktlklf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cfovfyla.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2yqjuaxtt.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gt2rftzdkoo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymusxhbt.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2cjrdaqox.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gt2uepzbenm.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2rwzijzlw.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2ehxzqdng.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2aaktcfhk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2xppuqrfr.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2clolmuia.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gt2wqqpkfvv.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2oegpecmx.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2eminivxx.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gt2vhgusiyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gt2njhwfwax.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2uiqozspx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2goneteav.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gt2hzubxnrs.html


<!-- 参考信息 -->