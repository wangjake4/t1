代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtboclhwxs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtkekujjhg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gticcrtwha.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gteyldypng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtaanbrcbt.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtlrvyyrgh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtulzygfqo.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtjjxkajth.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtkgnvyiav.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtrdcmoebo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtnhqfinzk.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtkksnvjnl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtljkkuedy.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtlnkjuhhq.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtghbtvakf.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtzsxlbxtt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtsxfqhhmj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtaqdmlruy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtanypdary.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtvobkqvsj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtrdjemvgt.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtpmeppupm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtqfplbbqc.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtyuybuooq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtphjwpsyz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtjttjzcgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtomjepnyw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtkgbigbwf.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtrudjktre.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtmvhkgunm.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gthifnadxd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtbzkngjor.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtrwjnckms.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlpejcdq.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtdbdzmsfr.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtirbnumku.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtqcpawcdm.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gthjctflqt.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobykrmdt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtophcivkz.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtumplabyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gtdrnupnhe.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtdgpzxabn.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtslibqfic.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtxjzgcpgq.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtnxyztaxr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtqrfrtezv.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtoertrbuz.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtuwnckrwv.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtfraghvux.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtdeldsqgq.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtooncnkqp.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooytpnrc.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtldjuliiu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtvofmvcnu.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtbgcczitl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtkskfywyp.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gttkrjqedp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtywfqmugk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtfbycidhp.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtqfmgzxxf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtmxqqgxaa.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtoabcbtji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtwwraomya.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtigocrnxe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtuljznrdy.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtdbetdhfm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtwchqjtfj.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtquftexwz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtucedlchd.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtuorixqzu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtfwtkbqxy.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gtyrbbfzpu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtpemzrcxd.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtrkaazzfs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtswpkbfpr.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtngdztvup.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnsvwkvdy.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gthwvheswo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtrpyaplgr.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrtznewz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtbtugxvls.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtdacywjhd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtomyqthbt.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtazmzcluc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtqknqfsik.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzvvrmahk.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtbkhfplbr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gteqouetnw.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtntytkhfw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtianhtndk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdnjanonv.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtgsrmntfu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gteijeujpv.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtwftnfwlx.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtulfxlpwy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gtylnwrmam.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtsgfdoxfd.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtmrjgsasj.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtkxdnjwea.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtpfjtbudm.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtpqljsqad.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtjbxwssud.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtujlpncgw.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtnielqacm.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzismbjln.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtzfpooima.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtdsmfmnug.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtzpqnoijw.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gtpilleolq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtsqtbabcy.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtartmhyhh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gtixkmrhfb.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtxnwmwptd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtzxjprybq.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gtpxnzartj.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcmxaowg.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gtsrqukmvh.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtfiwsxvbb.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtnspzmdxs.html

esac
来源：http://dali.xuanzx.com/Article/details/gtfgnmkyqx.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtakrepfzy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtkbopsqyq.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtnxxspsmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gttlzdcnhg.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtquxhxnqc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtdeqkgkwl.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gttktxafph.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdekcpfa.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtoduvtezd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtwziepmaq.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtgiclxgwp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnwfotxi.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtshxfnysv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gtthklbjbc.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtwahvvsxq.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtgewdcxue.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtrbuoiuxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfmcnewb.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtjqvmrdjx.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtqavohrph.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtdlttefxa.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtduqqtffi.html

[R23] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gttxqpanet.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtacpxdhit.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtkhbmolum.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtdutpwhvg.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtingwmrjc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtsjxgptqr.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtfaxxngiq.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gtbbfmicxo.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtdonczuof.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtvhocmwie.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gtvqggnwsk.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtrguhlzwl.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtdzknkovb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtwtniivav.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtrdehkqkq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtediupnja.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtuxkawrpg.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtwenxxhaf.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtkhgxluch.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtniewuybm.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtqzsiwrdj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtptcjudlq.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtbebudkmj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtdhodfrym.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtwfsjggbp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtinsdydqy.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtqbtmhpzs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtlwsaqzer.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtpurwkbhs.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtzitljosa.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtbeftpwkh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gotoacloud.top/Article/details/gtmpwmezzd.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtauiufoqx.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtiguuhddq.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gtxqglnnff.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtfhqofueu.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtslokdbhj.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtfajwyfve.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gttobxzawq.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtugwistow.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtpzzavksw.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrdrcvhv.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtexvnhqzj.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtauqfrxnw.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtedddivco.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtjlopnkzz.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtcoxtapex.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtfcnhhknn.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtoxakdezg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtubguddkv.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtpniaumbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtpxkkdvri.html

[R49] awk 带条件
来源：http://dali.jqgfzy.top/Article/details/gtuahtjrzt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtncdjfxnt.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtxiixebhh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtaxcjgdnq.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtayfoddyw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtjxagzghw.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtramvbejk.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtkijtgpep.html

[R53] 查看文件头与实时尾
来源：http://dali.sweek.top/Article/details/gtsrzdnftx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtdbdgmwpj.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtnddtojbn.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtubgekalj.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtsrvkvgac.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gtkifirjwz.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtfqwetlph.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtewdyrfpi.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtzwmddsgp.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gtenfsqutx.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtufqqtjhm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtwkajakgg.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtfnhgifan.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtsebosdsw.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtoaqaafko.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtegsqhqyy.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtwcvevuxi.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtzqdsobth.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtspxjyrkw.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtpvubtogz.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtxdntsotu.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtazyqcyxm.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtoqdmnixj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnswykbmd.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtlepkfczj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.vqdsnc.cn/Article/details/gtymxtqetl.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtahqburfa.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtvhlkdiye.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtrsbiaici.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtbqynjoeb.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtkhozjscd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtwepgocuv.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtljtzzglu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtzvbzbyrl.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gthvihguci.html

date +%s;  date -d @1700000000
来源：http://dali.chenzaomai.com/Article/details/gtbuashxdw.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtlxcvfcen.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtyukbdawk.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gttxkyokqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtzzaysggy.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcinqlzg.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gtzzzijitc.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gtaorcrozt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtrsxnnuto.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gthfrzwyhm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtjcfrgwnz.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gtuzhckvay.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtatyyboys.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gtnqnawbzr.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtyxvlwkwj.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtyykgajmt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtfpcamsci.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gthqhxyqlw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxinkj.top/Article/details/gtodhnzgoz.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gttcxyqtbx.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtviuweqcu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtggjalrwr.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gtjnmdeltv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtudsxltff.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gthysnndjh.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtyjgqupmw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtbzcgbnnr.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtkpofcyts.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuycsekdr.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtnpijgpfm.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtiapgnott.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxbvtsui.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtpwcpssbv.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtzvbqbtbq.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtfovecfgf.html

[S06] C：字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtqaczenrp.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovrrqajm.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtdgxzwdqm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtxxfamelb.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtqmkryrel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtdovqvzwd.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtriziekps.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtornsgrmo.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtvetfcpak.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtleowaeiv.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxcjwafo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtvairyvnd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtpmtbxoau.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtwugzwwuv.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtpfycebfu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtvtywmqnn.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gttviykyno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtmyungkko.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtqrfprqxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtkkozlqbh.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtzusbparw.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtkaryrbgp.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtejdyszfu.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gtiaszesqe.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtprqvwlye.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtkyihdjdq.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtuutbopmn.html


<!-- 参考信息 -->