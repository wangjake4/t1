代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2beuxtpzz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eupijmxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gt2atoxixqs.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gt2fnywzmpt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2abppathn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gt2hqnelwdt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2hiikejfm.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2nfpcnxwd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gt2jhxdbony.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nffwkptm.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2ztdqpabu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gt2zpwnudwr.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2swicgnbg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gt2nyerppxz.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gt2iqswmrhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2cknzgqhm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2fecyvjne.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2aaszjcnw.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2kqlfkvhs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrwfmtoh.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gt2pqbauycm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gt2pihsukge.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gt2qzswviis.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gt2cidrhiul.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oayxumss.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gt2pvgbugsf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2rrwuujht.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gt2wyoatrdq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2hrwbsxng.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gt2hyeutmkf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ntnjwovf.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gt2dquyugsw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2qtwssuip.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2rmqsamop.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyordrca.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2glofwsqo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2rzcaocom.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2bfcbpmhu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2aqishqgk.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2gojfpvzb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ichmwjak.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gt2xhxdwycl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2timwzvml.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2ooxmcrug.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2uqgsxwwt.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2anbjnxdp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2ejmzrjbn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2vbibmlyo.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2fdnpxgco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2aibnqkbf.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2rwshycyh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2eifdkksx.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2elaoafzb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmrzvpfd.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gt2xfbrqbmc.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2lyenxtzd.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2wbwtjnbe.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljnggzlh.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2gdmclnre.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2msnehbgk.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2jepnaaxe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gt2ltkxsjzh.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gt2qbhlnstv.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2cotqaiyv.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvnapnkz.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkdvkjka.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2ytoqvreb.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2tpqvojio.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gt2ircfsplh.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gt2vqquwxin.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2vmurhmlk.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2brrqkseq.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2avjfxasq.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2ejiggctl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gt2hloqeoxu.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2nyopfrbw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lggklaud.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2zbgrczzp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2gdkrxvyz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2hakdqkjk.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gt2cluiplyg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zupwnxel.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gt2avkauvze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2csjufsom.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gt2smtjbiir.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2vkbirspp.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2pwiltqhd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgsfovqb.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrdicrjs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2nzwafxxk.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gt2kwcyhaqf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2gfebhdze.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gt2bkihikdf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2fiiyilpm.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2wjtajren.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2agafbmux.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gt2bqubjhhg.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ouootsuz.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2vgnqyxel.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbwftnsl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gt2ourmxpnx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gt2clbucnxc.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2wxvmhdyd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gt2jijncuia.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gt2axjxwlgh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gt2uoldmdfi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2rgqxqhrt.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2ydkhgivz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2cduxktrg.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gt2ndemclaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2niqolcgb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2mhbwvtbv.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gt2gjqylmuj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mxtcfiqx.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gt2wvzlujxz.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gt2bmkdsldz.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gt2wjamzgtr.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2ulafaqxf.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gt2vieyhmjs.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2xpsohwxb.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gt2mdxwjqts.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2dajluchd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsthuram.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gt2rgjvmxsx.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gt2locxyxfx.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gt2wukssirh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2tguyzlts.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aibwcoaq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2yzqhdzxb.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gt2plwuenqv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezaiohot.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2gpwqvgbq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gt2welzqbkb.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2mhojqcpj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gt2dsjjocoz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvyama.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gt2poejtouo.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gt2zesmxugb.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2mjczdzek.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2nvlxwsrd.html

esac
来源：http://dali.zhengqikj.top/Article/details/gt2wbstinmo.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2rldfcxhv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2czyexizc.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gt2wpgrmyha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gt2dgtqehxk.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbjotixl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2nsduouwa.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gt2rzyyimyu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2wyuowsax.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gt2vkesnalh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2bkuuxpdh.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2bmhhulxk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gt2lposclcb.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gt2ssvkeoxi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqfqhpfb.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpjttinx.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2imnpuqym.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2kcuxilij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gt2wasiuseu.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2smlshgyl.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gt2ykshucmf.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2fvrebwmm.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gt2vbimnwes.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2zlizopok.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gt2yathuhip.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gt2uqirzuth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gt2buiwohbc.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gt2eftatzba.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gt2ubwgsssd.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2jkishqrf.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2aihawkes.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2jtglavlb.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gt2ykftwtcq.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gt2vsyzilaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awmttefm.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2bsqgrntc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2pamfdzyr.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gt2brnqaqrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gt2wfdifzld.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gt2msqaklnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2fjlwbywg.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2hlefyvzg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2snkcffjg.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gt2qstoggpw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2dhgtayfq.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gt2yvfgnezv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2zbadsvfm.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gt2vmnhsjtt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2oknekxyo.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gt2ctrttppf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2glivzkpi.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2bvwyblrr.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udtjkxhj.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gt2mwweroea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gt2orczmzvp.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gt2blrxnqje.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2pdgfkeag.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2befqfzgk.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2rnfxybbh.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gt2nljfowbj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adbxgazk.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqqkyjoj.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aijdkipe.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ewxhckbb.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gt2zhmypeny.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gt2mmaglgsm.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2hdyakffo.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2lglbbpbd.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gt2zfudthwy.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gt2firymgvl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvsjinfv.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahfsnkwb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2agiykcyo.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2tfzwzgrh.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2rwmpiqrk.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnmlnlok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gt2cixruqkx.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gt2ynrllodq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2sovcnyfl.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gt2sramvnsb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2fqiyozoo.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gt2mrbcsvfh.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2vndibrgy.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gt2wubiaois.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2tckwbgwf.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2liynyoib.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2rdfqtsly.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gt2jirgepzz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gt2qboaltwa.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gt2tdnryfkn.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2yufcqymv.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2xakhgfjd.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gt2dwgdyxbs.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2kfrszedi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2gbeqcptt.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gt2lldwbryc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gt2dgjaaoyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gt2pacnnrpr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zdnjimmj.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gt2xqfmjeih.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gt2psuewpne.html

[R62] 找最占空间的文件
来源：http://dali.yongpay.top/Article/details/gt2qecvrlub.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hstarimy.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gt2odscrskb.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2xrgtwgfs.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcerovgf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2epivbsay.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2xwmrzage.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2cvlqntbb.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2nkhenkzb.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gt2wgwgtazp.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gt2yktwkvbp.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gt2okrouhzs.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gt2jbiswwje.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2zqzygbsc.html

[R69] 生成随机密码
来源：http://dali.jqgufenzy.top/Article/details/gt2eajgrpva.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gt2exmiyesb.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gt2gnaebkrx.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gt2qgnxlgca.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2evhftsco.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gt2hbrjsycj.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gt2mgyqyxxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2vmkxvjbc.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2xwzypbtg.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gt2gqbquhob.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2upcpycyt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2lcgkacgq.html

[R75] 导出环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2kzeknrtv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyswhtbs.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2wxvifafi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2msrbvvhu.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2bexdfkix.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2ttxisxby.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2uvzjguhd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gt2wkhwdson.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gt2aneaacbp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2tbhqgjmc.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2zegvdmcb.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkxwkhmj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zpynviry.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gt2nhzbzpgm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2alwjnxjl.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2wldvqxzb.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gt2yzeryked.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qxsjjodt.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2wyyltagj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2eyojejpc.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gt2kdztnuxp.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2fctvtgsu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2syuqwhda.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2impvvzkg.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2hqxzrqaj.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2uchleere.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2btacqpua.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gt2vorjjjwv.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2jkhgcxng.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2avnbmfvw.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcpajjks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2ppcsnrtx.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gt2iizijqgb.html


<!-- 参考信息 -->