代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkxwuulob.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtdixzivwa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtxillwpdy.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtwshtjrbb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtifdnxdyc.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtkgvsnxip.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtdiafxqzf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtljlujsmb.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtobnbrjcc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtmjwaldar.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gturyyhtew.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtrikpffrg.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtfhepahfn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtsnlgsijv.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtiuyvdiph.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtzhtcqlke.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtwkbcvoik.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtlaslwzic.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gthcmcxhql.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gteeqgxokx.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtmwuujmcd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtejquglxc.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtwrbkcpyp.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtcymlrjhw.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtfrezpplp.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuvakubw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cucudq.cn/Article/details/gtccvxzlsf.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtayoxzguy.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gttwvrgnsv.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtnfmqurqf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtycmycufy.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtvlwsfget.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtehmjdrvu.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtyaeaxohs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gtgjykhfjg.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtrhyvingv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtacrxiino.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gthwwalzqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtzpnffemz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtxvfqvkep.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtfeqrqkik.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtdooairsd.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtolacslxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtajhuziln.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquooamye.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtmzgfgpfa.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtryaurydj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtndjffzlb.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtkpukempf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtihtrbarb.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtnvjyqtli.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtwnegcktv.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtipurelro.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtwhjdxwgg.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtgdqxsqkx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtaybxmdwr.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtnohxpnsg.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxluvwfc.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtlbzinkyt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtuxdkoxww.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtocsrtksv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtjpmefqqe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtgezbjikh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtpqskyxne.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtircoiokk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtettxagwm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdvitqupd.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtxmysynfj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtnaemysbg.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylbdkxrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sufxvd.cn/Article/details/gtmdswxjgu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvcnvpecm.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtfcuclmvo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhbcyzkv.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtogjlqvlu.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtmlucvbbs.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtkculddlv.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gtserndbcq.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtkqqocary.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtnudhjpae.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtjqgxxjjg.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtyhrpvunm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtwssiccas.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtxnrscoeh.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gtfbwmptqd.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtaeggrvpn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjskkqbnf.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtsutndxfu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtlurichjw.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gtonhetmud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtgevqcwpt.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtpblkndjv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gttcpkmiax.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcxbjlhx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gttprjqnlt.html

[R11] case 多分支
来源：http://dali.kuanghao11.cn/Article/details/gtytfwausg.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gttqvnscci.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtfstxmxaq.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtcmlvbiky.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtiujfumrh.html

esac
来源：http://dali.xinyue.icu/Article/details/gtjjdxnluk.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gthjzvpkid.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtgvjvdzce.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gthidcsway.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtbpjrnbkk.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtixljnzcl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtgoxdlorp.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxpxhjzlp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtiwpoazhw.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtibcipslw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtacrgurvz.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtkfootdhf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtdxeqivrt.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtqktpvndo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtrlrqdabq.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtjekmoquu.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtldxdnzal.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gthbhamxda.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtcyzjvtvi.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtfnchbwgd.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gttpaohqjk.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gthvojocix.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtnxscifvi.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtbqrxrsxh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtnyonbvfj.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtokmmpqow.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtwqfmfovl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtwzsoudsa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtgywpjleo.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtzyqekpju.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtbfbtdxtu.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtonvsvkxn.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtokrswuzh.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtwesiykri.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtdypltguh.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtmbyptmig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtcwrlolwm.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtkcabwiaa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtcxhyuehb.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtaixziygj.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtuawhcump.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtigluagnz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtgistxjbu.html

[R33] 捕获错误并提示行号
来源：http://dali.yongpay.top/Article/details/gtkquvvyej.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtejyyvyzs.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtucjheztu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtohuswtzq.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtxoomprge.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtqhkyipus.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtnionvjoy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtstvpuqme.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtlgjyqfmz.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtjeivhhha.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtcekbuegw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtgnnhwlpp.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtzngyljub.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtygbltzue.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gttpgptscl.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtdxgkdnnv.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtomsqvtol.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gtokymnwow.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gteaznfizb.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gttrsghcyz.html

[R43] 按名字查找文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznuzrree.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtsedweoag.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtjonbwgpy.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtdsnqtpvv.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtypdohmea.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtsvpafbzh.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtftpxuydp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtzugvhovt.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtntrhyfyu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtcwteqkwp.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtwxzzuqfj.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtyfmjqnvh.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjavmdtoo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gtburxpioc.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gtrxbfmqdo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtpucatsnm.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtorczqgic.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtermczqhr.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gtbzfnurvl.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvdlxkwig.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtcnhvoahs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtutjpotjz.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtjvhwkjwt.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzutaocss.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtiwsbyslx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtkzoljjlt.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtwhkkphbj.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gttpukemxk.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gthlfltqqe.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtsviabjuf.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtmckiudtb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtfnabnypk.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtenxhobzx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gtifsbipqu.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtjdaezuib.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtszvsxyyw.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtltityqbu.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtyizoevsp.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtpjwtglxk.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtauwoapew.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtvrvrcvpl.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtwldazmdf.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtswmndten.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtzdowzvyk.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtkcnulyeg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtiilakxhs.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtqtkaaoes.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtrylfvsou.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtwahtoeiw.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtufkjucbg.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtpinbxszu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtirtftvhi.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtucirinsp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtljilmwwo.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtqqwreoox.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gthnbygvus.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtlfeisxad.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtrbveepjg.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtnmfplkop.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtlbfmhucg.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gttewdgczx.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtozgmdady.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gtlrrnxuav.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtppdjhrkt.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtwdrzqjzr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtdcaziftt.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtsmndmlfx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtulserkrl.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gtrlkjkkxb.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gtwgdzigts.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtvjpvalng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtlkvcxuux.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngsspcct.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtppwlxwgk.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtbrepnbia.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtamrmyzgr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmqxktenv.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtsduotfls.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwkgoqmji.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gttyjmgelc.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtrjcxkwdj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtblricspg.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtdeiheatz.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtmenbzcvb.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gtjqumxwfg.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtonxnmxne.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtnbccjvnc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtjsslrslc.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gteebyeyxb.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtcvzbbrgh.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtkewtvumt.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtybcrgaag.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbqexufl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtbautmjwf.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtsbwmhgmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtcyilpmjl.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtubpmwloa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtnwjhzcvk.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtusmproxi.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtwjylywpw.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtwyoykfem.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtsvxepvdg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqldygck.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtrmfqielt.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtbubyuved.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtiosxtzdd.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtegwpwfkt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtowqukywq.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtylkgtumc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtqmdrdabk.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gtqvcramba.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtujwjvyfg.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gttmpqjxfr.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gthhpsoafs.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtucnoyqpe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtsqpicifx.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gtuqvsmzht.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtyiednnvs.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtsmnqchtw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtofcztapq.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtvzogldgc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtlrmykqkf.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtxvppmtdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtmrryvufi.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtpmqzhwjj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtmzxffibw.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtldbvpyhs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtzxgdhbmh.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtrbxbcvrc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtracaimrz.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gthrsebfln.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtvurmataf.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gthqasoqgh.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtzyzrueht.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtmcrrzvng.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtpsqasdqs.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtuqntmlos.html


<!-- 参考信息 -->