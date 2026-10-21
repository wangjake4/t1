代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtyizvvpcp.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gttrbggozz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtdosqanhl.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtocqjputy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtspjuywlq.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtmghagiyn.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gthmicyqev.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gtzyzzarhj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtkuxgrsis.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtzxaifhhp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtdsdfqpgb.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtgkmgjgfk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtljgykasa.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtwwgoxfqx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtotzogywv.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtdansuwvk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gttnblnyua.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtjgwajrpk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtkdyceoak.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtmcfamzeo.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtippzcidw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtybqtrqxh.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtnrciioen.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtmtdcbxhq.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtcnuoztzh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucpealfa.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtvfzcqobw.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtdjzoeips.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtelzalixe.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtwhyoskoo.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtlbqcgxee.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtrpwgeaxy.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtviijlowi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtrrlsdrnv.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtqutijxjn.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtrndujoig.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtcsymvohc.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtpkppriry.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtedfnfkih.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gtlqgsumfb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtkxvzwyty.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtgujrecsu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtaxasibge.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtbsnoirjl.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtebkzaeaa.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gtsxktmscz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtbylntlsm.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtccktxwmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtgozobesw.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtxtacpzql.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gthwlkoqdy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtimbxyzsh.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtzbrfalgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shzxlz.cn/Article/details/gtefbpuemb.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtcuonuert.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtwkvlwhso.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gteezmgsxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtbepqvydn.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpryywbw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gteswpylad.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtlrxkelgo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtlqnlzxqo.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtshkwktdv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtjvjdzamt.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtylyixruw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtoablcjuo.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtkpvpukpf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtsbyxmpym.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtoorbxgql.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtxdvfydxy.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gtbdlxpbyy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gtqaeekleq.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtwezaqhjf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtcbzljiik.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtxpuqcbuh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtuceamxus.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtmaatjdmr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtysfkqrrc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtiujapmmm.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gtvynsnzgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtgbltimsl.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtvlnuhvxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtrlarziud.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthxorypxg.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gtvxtjqscw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtftreolsx.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtlgmvfqfq.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtodoztowa.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtgvvmfzkh.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtzvvcwcso.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gttdsqawdr.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtdzvigvtu.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtkfmkfwyo.html

[R04] 位置参数
来源：http://dali.zdqjudy.top/Article/details/gtuufbhhnq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtsowssiyu.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjliiijp.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtzkeadxwf.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnrjextu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gttbtgvxgd.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtwxdqhvvu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtmalawxzf.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtstibynwo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtxznykjtd.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtpmwfrggu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtjpjleh.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtywxkscyb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gtueibekll.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtbamcdpxi.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtwhnvpmhg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtixykjplb.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gtxtnbzkgc.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtxmwibxdh.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gtjmmwkrkj.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtjgeknhbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtsgogltbj.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtyhxbjbsn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtomsiatpi.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gtnbickaju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtnygzjlbk.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtupotlkln.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtjbackiyz.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtqkrrhged.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtoyfoqhcf.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtltzvzhih.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtdeuwtgiw.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyglkkza.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtpyizgnfd.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtlmjbjbjv.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtjhpqbrvr.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtsafagyfb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtqwpwuyhr.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtgjcwmbpb.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gtdunkllxi.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtknjmbwkm.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtcdzmiavw.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtorzjtdpa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtfcdbyygr.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtqbwdmcav.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtjnedcybh.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gttwfegyxa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtlbzxgcyp.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtrqbpntgh.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtyurfirci.html

[R27] 算术展开
来源：http://dali.aizwys.cn/Article/details/gtcqgybruf.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtwmcekheu.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtolmnscsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtojzoxmhw.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtrsntuwhw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtumojtveh.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtpzazywbw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtskzfesyi.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtwerhnnil.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gtmhkmhcwg.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtoalneazi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gthzijlqju.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gtgrzfzudl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtfjnujbtu.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtiglvsngd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtwtdzgrxp.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtmtpjoiuj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtgrwebves.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtwdzlsrpq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtootezcmg.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtmcxceynm.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gttzaaqewr.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtjgopnuks.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gttnfkrsgm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtwwnylrpg.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtpowvurgu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtqpchreao.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtybsmqrws.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtmsdqcgqg.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtpmgvyspa.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gthbyosney.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkqiaoio.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gtzkpuxiax.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtrsqifcye.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtbdieqypd.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gtvcrbfvhf.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtghjjzlgu.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtaqknrqlp.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gthveeprhp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgfzy.top/Article/details/gttdlpmruq.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtwkyufwwa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtkvkhhinu.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtalsuuiqb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtdlxedqyl.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtjlkybrlu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtcrglufdz.html

[R50] awk 求和
来源：http://dali.zhiwuduotai.top/Article/details/gtlrbqdpyg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtxoxchzxk.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtmofmqapf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtdvcgvdrt.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxldtvbv.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtzwwyotkv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gttsecjwar.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtchsxrgmu.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtvfsommcs.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtvouvxgmb.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtmyficvem.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtaivdzsfw.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gtgnbmenkc.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtjvkprcwa.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtbhtfqyzw.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtzujfhjcw.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtjdziolbl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtlcxdryfj.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtpjhfwzit.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtjtfosgoo.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtczrceuvk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtocltxcxg.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtpdwzvsqm.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtsrrvddfd.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtonhbjqsk.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtxtlicpnr.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtcnxxwehe.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtkklnbdkl.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtlkjdovch.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gtswngeugw.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtueznjgck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gthokzocpy.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtyejiuhnt.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucxxpiqo.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gterhzxzse.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtidgcbquz.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gtquxjrilr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtsuhmlmuu.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtbgsrxngh.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtpymtuivh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtmbcpisou.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtaqihwvsf.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtbvgvgpjw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtvhkqxjlu.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtmzteslcu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gttfuehldo.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtcqktxtnw.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtptcoeqma.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtldckdxii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtereuewho.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtedgwqpmx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtwlbeondq.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gttpjuncxk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtmfwodxwc.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtqhhukgaa.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtvqvasgko.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gttvhhzgwr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtzsjexiih.html

[R79] 解析命令行选项
来源：http://dali.yj20258.top/Article/details/gtukqnivvw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtcpajqkwn.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtskqavgso.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtjmqfjitv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbbhuiyfi.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gttrxjnyor.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfvxqqlai.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gttvfaleiq.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtzxxhgjle.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjodstrn.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtrjaeaotf.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtcixkhtff.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtalgufqfu.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtufegoprt.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtxudpkurs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtobnikeye.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtogeudmoq.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsmadjhl.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtfkjeyltg.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gtxtqzlhah.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtcpykqsnp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtkhvtqgjc.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtaduncpms.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtunpqtdac.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtmihhwoqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtwdbqqnuk.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gtctdqupva.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtsmlqpnnw.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gttnbnsyyi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtdqgbuegn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtcxeynotn.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtqzgyfect.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtbacycifi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtbioxjqou.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gtfjkndkmm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtafqodtlc.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtxgzrvubv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtaqajkkfk.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvgflxpvp.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtyqnhupql.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtwyatuvog.html

x |= (1 << 3);
来源：http://dali.pycfn.com/Article/details/gthwomhsvg.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtoszrhyma.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtvpcuhcsh.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gteycldrne.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtwduvckef.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtvqehekqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtkrcfouhv.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gttausjxva.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtoblvhsvu.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgkfiwph.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtneulncln.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtppdvfhcc.html


<!-- 参考信息 -->