代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtaqgklgqi.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtohyuntrk.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gtzkinkhga.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtwwlbaghd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gttcxmtzmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkubbtcjb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmyuxxab.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gthqwdhpuk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gthcnwnbfb.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtdqliwafa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwallrjoy.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrvlikzp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gturxwbiis.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gttfiuvjik.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtvchyqmyr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtdvystigw.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtryobqvqu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtqnachfya.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtgjbgxrhs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtynfzvcyx.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtkzepwcuh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtkycdmtgt.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtswkgqpho.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtyktkjomt.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbjnxduv.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtkkopfqag.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtjfbwmqii.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvpllypu.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtressmwoy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrctzfrxk.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtouawtbxh.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuikncqq.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtrmasowdb.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gthrnmswlk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuxming.cn/Article/details/gtxgbvcqcq.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtruewaieb.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtmxtpfsbn.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtmxorljiu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtsoliqhpv.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtfonnawgh.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjtxdolov.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtrpfgpwyl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtaztciihp.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtotpaxjyv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtdhvbchhc.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtyxipysbi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gthjglwdpk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtcjmwmphq.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gtsalgejay.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtzessomqt.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gttandpcfd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtcpwqewbn.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtsovdpvfe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtjhcmwtif.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtqduangpv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtepxbytes.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gthjakudnl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtacwrtrrr.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtpnwizwuu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtsbpvbrrs.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmdgwmyx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gthoexgqvj.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gthmohfqmn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvjauoakj.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtpiznfndr.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtnsyvtkjv.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtwyacjmye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gtambwjjrz.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtwhbrylse.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gtkrdkrovo.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gtrmhbvsws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtgeewklwn.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtrdgjtvxi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtxzpwdzim.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdkhrdgmb.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtufhgqtet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtoddypjsm.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtzqsagtkb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtmeikmggv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkowwxthx.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtlyczylih.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzyfqcal.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtvmpxcqjd.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gthnukurze.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqgjwzyg.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtqtotwhvv.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtktkyvwsf.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtyntwtczj.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtdkdfijfv.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtcpzbzxps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtismctdcq.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gttszakpwd.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtopthsrxx.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtufinqrtf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gthdidxxec.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtytgedhic.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtmhxtpdqq.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtuufiipwe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gthmgkuslv.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxnrjqkg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtshytnkho.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtbefhmtra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtilvspzzq.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtndgipfin.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzwirnxl.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gtcnizompp.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnjulvtl.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtrzzbvnzq.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtyyyxyhql.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtzkufgfbs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtikxciehd.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtcuipgsge.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtqxlsusoj.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtjrhxqizq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtgogxzxsn.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtblfnjiio.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtpbaziaxs.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gtnupxjejk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtnokfenkv.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtvetrshxv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtfvilmzdx.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtlagjjwpf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtwxnfzduq.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtijtixaop.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtxasppman.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtjyavzlqq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtpuvhrfjd.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtkjavnogc.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gtpmtuetxt.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtzhlgsbot.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltwkzuof.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtgstrpnmh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtyvxcmeiv.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtcksbfewx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtbhfscrym.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtwrsdskly.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrpridrrp.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtsjhcriyl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtfavajjdh.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtfgmtxhdu.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtossrbdkm.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtwzvlznvf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gteutuagxt.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtafbdqscf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtdyesprsa.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtmprogiyw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtpgigyaqv.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtjpkikbtt.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtgynenpat.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamloixqg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtmnmlwpsq.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtdyhlcafs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtugtjtmvw.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtlrlvyuin.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtepwkbwsu.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtzzxjougj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtbbrctnqy.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtgcqvaeat.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtocjhxnaw.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtxpuhshtq.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtncqwifcw.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtsyvnilja.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtxolvchyt.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgfzy.top/Article/details/gtvfysmhfl.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtyjjhyarj.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtwkhjfpoe.html

echo "log" >> out.log
来源：http://dali.zhoulong.xyz/Article/details/gtuzwnivhj.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtxogqgehq.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtnemceoqb.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtxaedrktw.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtzyzilqna.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtyuxewlza.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gttpkncols.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gthliiugsc.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkckmwysm.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtkkrqmbrh.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtwdppueay.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtpftpnuxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtugeqdqxl.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtqcyguzoz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtvbzyfruh.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtiszgimxs.html

awk '{print $1, $3}' a.txt
来源：http://dali.yongpay.top/Article/details/gtwtdjcuey.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gtgsvncfbo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtfhwrrfwj.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtsrkxcahk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkgzsxvp.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtujhtemuy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtowqjgvvh.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtqijlfqyn.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjmtbdawm.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtkqcouupb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtqifkkwdt.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gteetqizak.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtvjogacyv.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtuxugfevy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtfabhhhbr.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtpcukbpmr.html

scp file user@host:/path/
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxooxaur.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gtqorattag.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtdgejcuzd.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtyroqmxsj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gteagekgkz.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtamuftvuk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gtppvaxkct.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtfpacckxv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtnaosubch.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtrhkjrouj.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtrzyeoygo.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtfhfrbqqr.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtakjdiyii.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotasbzvh.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gtingzpvva.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtusxbicwy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtzdmunbid.html

[R65] 查看端口占用
来源：http://dali.ydzc1.top/Article/details/gtmwckdgfk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtlzhypkyy.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtkrzfpcdb.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtqraogpbx.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyewvxvqq.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtqwgtiuvd.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtcaintydg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtkedyrxag.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtrtoapeiz.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtbwalkxgs.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtrapfarcj.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gthwtoaxgo.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtqgifhfpz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtmoihqgbj.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtykmiyycr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtdrsfeqwv.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtgeotlfpb.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtcmmmqyne.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunpzzvjc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtovvqjpyt.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtzslobqeu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gthjdskfyf.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpjcopkje.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtcjtlvibt.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gtlubenqtw.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gtgvphmobc.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtknxauirx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwilknxp.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtglyjeitp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gtwyiufcmw.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtzszohbqs.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtrjnsfruk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtywrbvbiy.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtmvwxglgg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdsymhcac.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtufgxazae.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gtvplxwxzx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtlsjswgdi.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtwutwyfvt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtcsoyejzg.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtsmrdcake.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtnngtdymg.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtodolhvyw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ybcxt.top/Article/details/gtkuipwxgi.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtijoamhyz.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtobkhjpho.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtjqpoasjv.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtaqcdgzag.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gthznpqcen.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtlchjggni.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtvzrsifeb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gtuandlzkx.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtfvzxfckn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtcgtqudgx.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtvhgxxvut.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpszzrii.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gteslltyhz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtobyypwym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtleetvbao.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtfewpzndo.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtizpswsst.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtxuavejso.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gtkcbgabxs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtvplqpqja.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtoqdkvnkt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtayevnxen.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtgeqiegqe.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtpihhbczb.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtilfypmsk.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtxkhdwibq.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtlxbvsnsi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtwsifqeuz.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtlpwdixil.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtzbieofsx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtempfzotr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtzxgywolf.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtbsnrlplv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtgmxkhrvv.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtimoebolu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtmayxizem.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbijfalei.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtsnsanyiq.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtvgkxrtsy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtpxmyyvvk.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtikrocfiz.html


<!-- 参考信息 -->