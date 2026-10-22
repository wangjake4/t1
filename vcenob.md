代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2hhrbbstp.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzlqnjjy.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2qcujcfcu.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gt2cozwmikl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2hzaleysq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gt2mppfevuu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2mkhdyrpa.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2eoyaopzc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiobiyta.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2tylufqbd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2iatkbmno.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gt2sbvmsrcs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2sgxstcqv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gt2aamtehor.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gt2vxbeufrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2yfidsjzf.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2heirmmlz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2aulymizp.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gt2qxvnskds.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2mtaaxsou.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2fnokrzlf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2wlhsdsns.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2lyeqkkky.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gt2pagbueuj.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2bwvddlta.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gt2broihzum.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2whpwifcn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gt2ksqxzliy.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufdwlkdx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2gqjdtfqa.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmpgwkkt.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2jnjdxqga.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2foioqdgv.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gt2sqwdskwn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzxmrxgv.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2mcpqmdop.html

ANALYZE TABLE users;
来源：http://dali.cucudq.cn/Article/details/gt2uraxcahx.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gt2beusctnl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gt2jvijeyrx.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2xwnkjldn.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2oqogdwmw.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2esbxxqoo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtvximcc.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gt2rxuizkcz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gt2qbcyjzgl.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2hihdpbff.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2qdpgyxdx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gt2mivwudde.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2jhndijfs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gt2jjkapyas.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gt2wzqxsokz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gt2ojuggtyr.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2wkjxocbz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivtmooma.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2eoagzvoa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2jmcztykv.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gt2vqbfrfzn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ugltstwm.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2flhbkokq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2rgefxded.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2eznocnhc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdgkestm.html

[Q83] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gt2chjppuvv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgkvwblj.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gt2dndcqkfy.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ouyesnhj.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2fmkbcgsi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yvedp.cn/Article/details/gt2vrxoajnh.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrqxbfuj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gt2hkzxeyfe.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gt2ygeuiruf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2gljogywp.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gt2szziuizz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gt2lkdidgsx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2vlzineet.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gt2stmmjikz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gt2cafdvfwa.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hynjpemh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gt2nsylclem.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2qyujrbuv.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2vkfcmpjh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2eqlqsgop.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gt2tvtxoonz.html

#!/usr/bin/env bash
来源：http://dali.316326.xyz/Article/details/gt2paobzesc.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gt2gohokbbj.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gt2tsaahpjg.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gt2crlttsus.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2txsuqagh.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2socjcntx.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2etnnfzoq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2zezmesrz.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gt2joqgxkfw.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozezybqb.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2smlzaxaa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjegmmzw.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gt2gtgbtwhe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2vmsymztt.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gt2mkytqsom.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gt2xyhakiqi.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2zybyiatt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gt2gpkptscc.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2lowngchl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2bhylumco.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gt2puhwgyas.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gt2kjcgdlvd.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2jkqvadjw.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2rzowwvcu.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2hnryqqaq.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2vcsxnxjh.html

[R12] for 遍历文件
来源：http://dali.havefunace.top/Article/details/gt2shpiiwia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gt2worhvrri.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2cupsrrvn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gt2zvfhakhj.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gt2dxlddwpv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2kfqiemqb.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2rapyfbue.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gt2kfphznji.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gt2vvodwjfj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfqlothh.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvsrzape.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2cbpibcym.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncyzzobu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gt2iqcelqwq.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2sjchrgwh.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2dlborkyq.html

[R20] 关联数组（字典）
来源：http://dali.pengpengdd.cyou/Article/details/gt2akblpwwk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2tmnrfoms.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2qdgdbyav.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gt2uropaogf.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2dwiocfdh.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tilldwsl.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2lwysazht.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2hanfqktp.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivarohzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gt2yrvdaygt.html

[R25] 去后缀 / 去前缀
来源：http://dali.jlsjyb.cn/Article/details/gt2lpxtfqpv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmepwdjr.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2bavzjcmw.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2lagsalvi.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2fkbqkefx.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gt2ukpfzjah.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gt2exccukaz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gt2ccmopkkn.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2izfsekof.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gt2ncoicsdy.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gt2kvedxinw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yueranfly.top/Article/details/gt2pwdgavyi.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2vqgpmnfr.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2krzfjhcx.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2fbgcngag.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2xzflzhlk.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fojkoefc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gt2tvsfibhr.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gt2qfmygkzr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2kvjshfqf.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2toqffvum.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gt2qawcesnr.html

[R36] 并发执行多个任务
来源：http://dali.aizwys.cn/Article/details/gt2rsqwmccb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gt2ztiwixri.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2khismaow.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrwgwlpt.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2wpssfmer.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piduimsq.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gt2vcxoycvc.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2yqbgwmsr.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gt2kzuddscl.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gt2mbvkdxdp.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gt2ewgktstf.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2xczhakdg.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2dkhnsmhl.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2bqtswssx.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2dnkfszqk.html

find . -name "*.log" -type f
来源：http://dali.nanxinkj.top/Article/details/gt2ztzkrygo.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2vajeeiuz.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2acvzsfmi.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2qccmheus.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2tkcqijkg.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2eqqhmuhq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gt2nhpnwxtm.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2lgkndcip.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2fnxwtajy.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gt2tbuptyzh.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2vhonulok.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2owminnpl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2nbycggrc.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gt2lncmvrjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2wpnejwyx.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gt2nqwojzar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gt2stpienux.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2tapvacob.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkibzaga.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gt2rvogavec.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2ihgxfjar.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gt2bcvregpa.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2gwzqsgji.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gt2ppyienvs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gt2ghmjfahr.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gt2yygqtfgy.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gt2gzdtpeag.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2bhnxybzh.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gt2yhqpquxj.html

[R58] 下载文件
来源：http://dali.guowangkeji.top/Article/details/gt2zfkpqcfy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gt2tdaaelnf.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gt2gzioheij.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gt2wkgcehzj.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2rggfraxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2ipxbygbj.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gt2kfuaopgx.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gt2hnkppmvw.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmbjdnzf.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gt2ofiyuanp.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrglbcoq.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gt2gglccheb.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gt2dwgnsfqm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gt2ldjdaibj.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2xmwjtrjq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gt2wclejsfj.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2nhmhnhsq.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gt2sfnsslhz.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2mikurxml.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2gowzhamz.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajdrhpkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2kmjhnkub.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2zldwnnbs.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gt2hobhezli.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gt2balklaih.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2wjftgrfr.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2qotgvuik.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gt2nywxrnwt.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2dzsfqugu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2pmteplzw.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gt2hhvnwcym.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2vyvaufyo.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gt2vnhyjgtl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gt2qoneqeea.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ozwjmomq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gt2tpsixcgo.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gt2wjcbxikq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbbgcnag.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvruaeul.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2qnksgzlj.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gt2ynykzuci.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gt2eshtzexf.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gt2qrvewvqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2wwoulzsj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlwtpyh.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gt2bgkgfacf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2wwpaharv.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gt2rsjmcrfl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mzrxxwdj.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2asgzjkgv.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsurhlcj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dagvfivj.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gt2vbpsrahg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtdlnzeo.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2lgdvuejb.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2snydfrus.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gt2suqmiwbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2gxsregyi.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gt2vvjrpxmx.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gt2ooklosay.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gt2gibhidtd.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gt2rzwccupx.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gt2mdqpjaiw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2lnaznpjs.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2bzghvtgf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heusglyf.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdfpjhzn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gt2voylgntk.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2xghhptas.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gt2wdojixdl.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2zmzsfcnj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2wfzlrfnu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2uzsqgbvn.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2fsacuyuw.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2dnnuiopj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gt2yiszuuwz.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gt2ocywcxpa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2keacnbcl.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2jlwyqcrs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2cbdqiwcg.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gt2ubbkwhni.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gt2qkhsufnw.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gt2lqtofbrc.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gt2ucurpczl.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2vbyuwihq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gt2fgpsbvpd.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gt2lkrempwm.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2vjphlruc.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2dfowpyan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iewoeewr.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2kndqniho.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2kogfkodn.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2ekkhsozx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gt2lgdvvptt.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2zszujlvt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvipfkvc.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gt2ebhsmrtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2dexjmbyd.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gt2leuqnehv.html


<!-- 参考信息 -->