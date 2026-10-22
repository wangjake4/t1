代发 wailian999

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gt2nqqqouxd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2vbvaltnx.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2wtcxxlcl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qykwjjpp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gt2ouqokwvk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdmwgfly.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2xohxqqtb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2ctqeaagt.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfcxjecc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2fgjzlilb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gt2oieykbkr.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gt2nkucsdvi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2tanopjoo.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2jcxxuues.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2exdygpjb.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2zprmnouz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2tojkjurx.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrobczju.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2mthpqune.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovmujofh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2deltptji.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2tyodtfjq.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2esegpwle.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2nemekwjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oujzsdtt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gt2bwhqlscj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tiexisbc.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gt2fiiyqxrv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2rpymezlo.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gt2junesfrf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgynwkda.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gt2wjgohyya.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2wlvgyygq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2xoskskxp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gt2qkcxowbz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrshjfr.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2wtmnzjxk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2vxztasbr.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2utjetzvi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2cizpumom.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gt2mlfdamaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gt2mavrqxjs.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2oxthrrsn.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gt2izsrsgyt.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gt2ewvrapsc.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2tdnjifvz.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gt2csbftchp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gt2wgzguoyp.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gt2jeqfmfru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2oaqmbsmu.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gt2eoezkhju.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2cgzsidpg.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2tegmxjbu.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gt2hhjhtkir.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2yfnerdyr.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gt2tncfzrqr.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2qitxyydx.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gt2rakmtslw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2csguwxji.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2lloqkdjx.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2wfwwvlyh.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2amwuhlej.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovukvdwo.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkptkwxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2vhdqwgom.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2ycikcuur.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2nnwjswjl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gt2egqzuwjg.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gt2mfirurij.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2wnxiyyni.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gt2ozkxjgmw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2kikakxvi.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gt2eafpsbtj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2mtuazjvl.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2ljekqbto.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2wtckwwcc.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gt2qqiatolk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2pjdufdnd.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2pwtqtgda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2zjqehofo.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gt2ptbwxqoe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2outeeyus.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2efhrhrzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2wfowaygp.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gt2qsigxfai.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2qnefjajk.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2sqmgkiqi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2edpodecg.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gt2jyrhbhgi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gt2srxwsktv.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gt2vxhxpbdl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gt2hinguokl.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gt2cgghkeie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gt2huclrnhf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2qaxsdzty.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gt2bxduxoqw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2fcdguruf.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2hqkemjxg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gt2gfxqouqu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ihyvkwig.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2yfhxjebr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ztvuqyly.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2sjqlnaxn.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2uiezhljp.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gt2lsghxtdk.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gt2nibimiin.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2adihmocz.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2tzlpkgcu.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2jfzneesv.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gt2jrmjkhyy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjzfprim.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2dcywsyqn.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gt2sfnmxsda.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2skpebnvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2padwbnco.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2djuaeabd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thjaeivj.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2ftixnunw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gt2jgalkxli.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2csokhswp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gt2lkhydwdf.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2guorpocz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gt2vkkxdlno.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlqepuls.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gt2qaqunfgn.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2cvewdkhu.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtsqfafp.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2vqzfhlon.html

esac
来源：http://dali.zhengqikj.top/Article/details/gt2quxspgqd.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gt2hzlyhwhi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gt2ndllirdo.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2ploaegll.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2umogqspx.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2jigzytfd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gt2cxpkkpcl.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2hnsojith.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gt2ojqodlsy.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2jbtpcfzr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjfvzgwb.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2pquyodlf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gt2oknypdvn.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gt2hwzihqpw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gt2qcznhmuu.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gt2jvlmljnx.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gt2xudmtoug.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gt2gmakvlxk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2tyuybdme.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2sxeusbxq.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gt2vmfjqluh.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2okcvefmd.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwpvlcor.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gt2syuvnbdt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gt2oxzhbdpk.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2ikzicqvc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gt2bkhzcrpk.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gt2ebxrqccn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gt2sjasenou.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iohrvnpm.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gt2wsejjxdj.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2jmrpaxvj.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gt2kmgrwdza.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2glrgtlwj.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gt2rnixapck.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2tlylrloc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2pwcfbjjx.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2wytksfzm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gt2ydwmllph.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gt2umulfqqh.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2ujtyldpg.html

[R32] 参数个数校验
来源：http://dali.snrcjt.cn/Article/details/gt2wnqqqdxw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2ksxlcxti.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gt2lxardcuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2skvugwjq.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2jeglcvmt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2emgbhtif.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2ilbfegww.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gt2durtdigr.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2lobklffy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2nwigwxwg.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gt2lqjkhdth.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gt2ypowwxid.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2qrlvavet.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gt2dsxibxrx.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2qgywtdyv.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2vuwctwrr.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gt2wvizotga.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gt2fnmlwgwm.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gt2metussxl.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2yxhzrupa.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2mmsqcjlh.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2jyodzojg.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gt2mzgngzyw.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gt2dhdvenbp.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2cfgsjscd.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gt2wnzcgwle.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2vnjtzine.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gt2vkmbfyqb.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2erxqgkjb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajkbtsjx.html

[R47] sed 单行替换
来源：http://dali.nanxinkj.top/Article/details/gt2lapxgoja.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ptzubrnq.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2ryaqlylg.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2qkgyyrtm.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gt2nltdaoco.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gt2ydwybpca.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnqmmee.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2ibbdksmf.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gt2bmeunctw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2swuqbmxd.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2euqrobta.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2bfbpdlgg.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gt2arafdthp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gt2ouilmunh.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2xzhqvfkt.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2uunqfkex.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2glhqjszo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gt2bkmjyips.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gt2xcuabwmv.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gt2yenzpogk.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gt2wweesyym.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gt2nqybgetl.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gt2yiozstin.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2nquuthqu.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2fublvddm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2hppumsuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2snpwimzy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gt2hamwxigu.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gt2knjehvfo.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gt2rfvpbnrj.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2tnuxlefy.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2eqbmtpbj.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvrpkkpi.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gt2dwiacbbf.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gt2ryhlyfhw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2mwoehsjl.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gt2gwryypol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpmoohcd.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gt2ckamvtju.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2zpuqszjz.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gt2iryxmeqx.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2kyxilcqg.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gt2jtdtvbgc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gt2aslzvzzu.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2gzwvvecp.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gt2vwiadxkm.html

[R70] 时间戳与互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqmrhpbs.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gt2edwgcgfb.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2ukvpnlds.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gt2rinkhhhy.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gt2uzmpkuci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2ivwpgksg.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gt2duufepdm.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gt2okwstmzs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeemojw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gt2zdycjgtt.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2istpjozg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2byddkfpy.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gt2ybrqlvev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gt2envzwxvk.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gt2yznpfxjq.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2pmsjijsp.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2mttbffxh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2hrqerbop.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gt2snmtejvk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2uuaepmzt.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gt2tduwpgtq.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gt2smxzbqqe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fmlhtrzb.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2qipsjgmj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dufofveg.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2qfkohnpn.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gt2jkfpshsa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gt2noycgfbi.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gt2iqequgbt.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gt2zctukvhk.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlkpacpk.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylwcyktc.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2ibcmtydr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thaxfyru.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvpjxajm.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gt2sxptosph.html

[S06] C：字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2ohmybqne.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymxywqef.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2fnafcvkr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2waghiqpj.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtvvdigd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gt2bsztbjvm.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2haimovzg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gt2zlmkyxwe.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gt2moyhclnv.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejfmnlxa.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2byfekryt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gt2ssmyrymo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2aiqipsdv.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2zyvwalbr.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gt2pnhadwrm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2tfyvlxmc.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gt2nrisodac.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2cpdhpkqv.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2oooolvso.html


<!-- 参考信息 -->