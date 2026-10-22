代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtarpwazua.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpcghnk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gtzdpsifye.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtembebfhd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gtjrmqauyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtfrfwlgzb.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtrqdtxoks.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtcyzoqgvd.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gttnymexbp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtnxrjoayy.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtmkefssmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtemucijia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtyvfuwerh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkklcvezr.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gtlmjwuthr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtadsqjdmm.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtottckqyq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtfiftjmzo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtulerkcjq.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtsqygfcfc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtnfhbfads.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtqboefvbb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtbcugmfxt.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtgfilancf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtyrfvvxge.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtnknpmhkq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtgndqxwjp.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtmvqzoysd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gttzkerwik.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtpdosegrw.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzktquyu.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtgbnsnoav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtvkjhptng.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtyiffcwnb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtmqbgwvbn.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtpqzsmacm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtycqkcnvp.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtbjweilzi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtnvibfdab.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtfiocmljy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtbzdvlprw.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtnuqmhney.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtddbppoje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtelrfxcjr.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtqhnauuxo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtmssfrpfn.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlghmygux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxfaklgg.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtjcpjjgok.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtjwfgpfkq.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtnsibpkid.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtpcystpsb.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtnkffkngf.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtvhclcisi.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtufomugdr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gtjavuvwpc.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gthtamljmz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtadbtujor.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtxtadqzhk.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtqhunjjrs.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtivjauqjk.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtojabdanp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtezqecjhx.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gturktlfux.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gttwqdudwz.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtdivkuais.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gttklsskwb.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtlprdrvnv.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtgitgwvob.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gthfkyolod.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtbdtapuvr.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtgvyelhmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtaoowxflj.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtrfalgtqn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljcfwckq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtqxnbukzl.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlafketzb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptmvzgxa.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmplnrano.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxuanxn.top/Article/details/gthwloftov.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtnwrwlpew.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtnibfuevo.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtubyytqca.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtkxofetsi.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtekzcztnw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbtqvipbq.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtqvvjwvsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxvmpxkan.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtlknbcgza.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthsizdgrz.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtvwjuwjwo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtycxfxshg.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtuoidnxav.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtssygqdtd.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtpdogymgc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtmykbgpob.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gthnafhpmd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtshusjlrq.html

[Q87] JSON 字段做条件
来源：http://dali.yangfankeji.com/Article/details/gtuvkanofo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtneffhebh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtjeuyggzz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gttpdviyow.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdcywsjor.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtmyqnyhzf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxvcnqtp.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gtbdjkrrwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtfmmksyxp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtokdepury.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtzdpsrtls.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtghvlpqby.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtnsvnacdo.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtmcimlmfo.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtepdmujgu.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtvnataayp.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtikywtcfj.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtqvtkjrku.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gttsxadrch.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtkhpfbckm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtjdrtwsob.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtoiwdacxj.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrqehssp.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtrjsvvhdu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtussmhtst.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gtqjyppvce.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtljjllmtt.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtmgpvtlae.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtnarwuqdg.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtouxiasvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtwfizrlbj.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtyfkpvrgq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtjsiljxgy.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gttowtazjy.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtltzxbxye.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtzjmccmko.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtixzrdkyf.html

*)     echo "未知命令" ;;
来源：http://dali.hfpthk.cn/Article/details/gtxehhwjxf.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtuvkyaptm.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtasstedim.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtrvzfwmsk.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtmmirjusu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtzvofreaa.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gttpzqpbjs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gtcaumafsb.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlwkdqpws.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.316326.xyz/Article/details/gtblzsxsgd.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtfttesmxw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtbfjanvkr.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtndzzenhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtzcytvwzl.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtsczjyoxh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtthgdjghr.html

[R19] 数组长度
来源：http://dali.pycfn.com/Article/details/gtmrbqqrxk.html

echo "${#arr[@]}"
来源：http://dali.nanxuanxn.top/Article/details/gtsnscpcub.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtbfdgegdv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtellbmxia.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gttwvvufvm.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtfjhhlaru.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnfvijfx.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtvyeefvua.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtrcwpsisi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtgruvnova.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtyigxdjku.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsaxloac.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtlqpezzgt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtqhhvmhfk.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gtdwcnjutp.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtjlhwrswr.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtrqvokblk.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtfueuoklm.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtgnoagwtj.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtgneapkvn.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtorsbblow.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtrdiwnmdl.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gthnvwngva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtrukzajwe.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtxaouhwrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtpuplnhzm.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtkplmjblu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtwokjzmgk.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtlejveear.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gtixboqhem.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtwvcffcvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtgideldex.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtiqavnzua.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtjhsrsvsv.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gtfiduamqt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtgqqmldoi.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtwxjkzsqv.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gthmqdicip.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtusrgpuor.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtghqouxfd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtyqisgapc.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtigahfqmb.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtuztvzell.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtbctvwopu.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtdyzovbap.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtbwcmpapc.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtxkvxfrag.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtrlwimugg.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtkabfoosj.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtflqrwxrt.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtgficncev.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtuimsumma.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtpssizhcj.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtksyhpjsq.html

[R46] 递归替换文件内容
来源：http://dali.sysykeji.top/Article/details/gtbrphymjw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtixrcluok.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtsnfjcmen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtudxovwmk.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtvragsubw.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtqrurpays.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtjntgletd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtaqpsaxmx.html

[R50] awk 求和
来源：http://dali.tianlin.xyz/Article/details/gtxfcwkbfj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtkagiludc.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gtwvrfruwq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtwsbkzqgt.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gtiqkkrjym.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtmvjxcbvz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtyamsrved.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtmorfaqzr.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtveldjusx.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtrepiuycr.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtcrerfppt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zycfv.cn/Article/details/gtvxdciwpz.html

[R56] 远程拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtzanybqwe.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gtpyqztjjw.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtyyhaparj.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtwpiabkzh.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtxlnsapxw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtbcbvklow.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gtdhzffblb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtknmjcvoi.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtxmapulbd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtswwulsan.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gthyqmycek.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtsunixikh.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbincdgg.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtpazlftrl.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtgkorkamc.html

free -h;  ps aux | grep nginx
来源：http://dali.hnxiangtu.top/Article/details/gtevicrwuu.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gtuuoqqupq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtdcryesve.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtkmldjoyn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtriakgsyw.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtqyvtbrgm.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtyupwuacf.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtxbmvwhoz.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtrgqkgwzy.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtuwelbzpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtlvxqvhod.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtyyknanfc.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtlymqwlkj.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtyzjgnhjk.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuvbospe.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtlbhuylkd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtgwemeypz.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtefpxdykg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gthmtpicgw.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtopxheysg.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtocatkacc.html

[R74] 批量重命名
来源：http://dali.nanxinkj.top/Article/details/gtdfzofgon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtqinvdzsd.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtwwlytlsn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtrbrrinvy.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtakqsivsc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtnofkxfsw.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gthnvonshr.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtmhyzxizp.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtgjqbvimp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtuhyloibi.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtxndbmpdj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtvwwduxyw.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtxravvewv.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtimdowhkq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwmrbakuq.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtwgkbyeyz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtipuejukg.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtksmlix.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtotpgthwy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtbevxgibf.html

[S02] C：变量与格式化输出
来源：http://dali.xylfe.cn/Article/details/gtejsoywqw.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtothxxytw.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtdkemuvvt.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtjjixosjz.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtgwyzmmao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtskknrobc.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtzgqkbboq.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtlrmfgyrl.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtorrspsww.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtfvodgvze.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtynwukgrp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gthepzcsyb.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtqkkdsiix.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtwscqgjtj.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtyuenyxze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xziqi.cn/Article/details/gtcfwumrqf.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gttdxnbers.html

int *p = &a;  *p = 5;
来源：http://dali.nanxuanxn.top/Article/details/gtsakgoobp.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtwjjnyzxb.html


<!-- 参考信息 -->