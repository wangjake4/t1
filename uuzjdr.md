代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2rhlzkqxe.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gt2siwlwsvx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2xhlrpdfq.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2jwzvlvww.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2xyqfvwde.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buppcbbv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynepwftr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2jknvdjay.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gt2wxaescwa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2owtpadva.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gt2krvvrymf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2ixeevzeu.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gt2wnqxstvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gt2jsysmtfo.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2hmxsgiiw.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gt2pywfxleh.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2xregqzwd.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gt2cwdfowuu.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2kmmyizzg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lypbrxqu.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gt2tjunlcel.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2wtlfqlqk.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gt2omzjbfas.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2halowxia.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2snwgrwvd.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gt2sqppfptx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2hesbreve.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2jotpwtxl.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gt2xzfwcguh.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2ksmdyfmf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2kcknjwvx.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gt2rcccoxpe.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wzmqiwpe.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2waixrffg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gt2lxmiedho.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2iyeuhcpq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2nwexaquk.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2eqjbktxz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2wspmlxlo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gt2biiwpqyh.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2zxiizrwm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gt2hmerdoss.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2ruvvqcay.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxtpbnpm.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gt2pgvalofo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2rouqmgph.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwznvtoq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gt2ytvlzxyk.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gt2vtnhvary.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2wojkrhhg.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gt2hidrfkvb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2ddwlnbep.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2ywmgzqom.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2judhrbug.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2vyafhtkv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2kljhwsli.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gt2gwgezuvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyhwuntj.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gt2ducqcvzd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gt2qkgimaog.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gt2ayxjvtdi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gt2zijpqrwy.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gt2nhahxnpa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cheryme.top/Article/details/gt2gctivaka.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2thmlvmom.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gt2stbjftrn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdzukord.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2xxgmbwpb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2ylqpwbri.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gt2axmusksg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2pwxfprtb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qahwdtri.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkijbsru.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2duideclv.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gt2lcutfbfj.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2dqbjjqwr.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gt2egxhyxpr.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2hxemygzl.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2bvgpvjnj.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gt2nfwqdhtm.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2qllhntcj.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gt2swolhrnn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yvedp.cn/Article/details/gt2tpaslobd.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2qcmqecax.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gt2bntwyaig.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gt2riumhmgh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2ufckwmqs.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2eeeklhoj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2ukdsnyty.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gt2lcgulbrc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gt2penuwsyf.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2ugwzkbwb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2jrnmixgv.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gt2rpteehmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2ruoazklc.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gt2ibiucoug.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gt2fidkzble.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gt2thuavtlb.html

stop)  echo "停止" ;;
来源：http://dali.fzhhl.top/Article/details/gt2nzdtyiyh.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2pzmgyhpi.html

esac
来源：http://dali.gogol.net.cn/Article/details/gt2nonvjwku.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gt2uvgserhh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gt2jwyvrijz.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gt2najihrcj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2vbyilrwf.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gt2hrmhcgdf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gt2jgsvlfmk.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2fghpcyvn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhrxejgh.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2tmzzofhw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gt2nvlfmqzu.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygflrwyz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gt2lvnmyjbb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrxhaem.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2wyzoosqf.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2ojrusfny.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2mjjajijp.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gt2bvvuhjuk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2ynemsrkw.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2gpehjefx.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gt2fijfkwhk.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2aavdtwpn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtwlena.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2tbzuyeru.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2nyffxxdc.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2etrgmjhc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2exsfthtc.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gt2ujeoawan.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gt2rxtakwnk.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gt2ajsixcih.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2gcpivjik.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gt2pddmixya.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2qeegtnxp.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2iriykrxw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gt2qkfebunq.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2uocgpkeb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gt2yccvbklg.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2zlnonqow.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gt2zcodwedy.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2xhugwrdc.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aebuawyp.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gt2rjocbpxx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2zbyqtfdy.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gt2xemcwxim.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2tjcecylj.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gt2qejxagik.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2ceffbxxh.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gt2lypgshmq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gt2autsmtya.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2anymzkmk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gt2prtvwhao.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjwvblgh.html

files=$(ls -1)
来源：http://dali.gotoacloud.top/Article/details/gt2slordzdg.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gt2ghzsmtye.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2weowbofu.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2lmfynalf.html

cmd > out.log 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2fuunvyqf.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gt2iwchgjxb.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gt2wiwvymyv.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2ponfmwmk.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2ychdymuy.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gt2rallyoob.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gt2cmmmatjn.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gt2gvowxcsc.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gt2nfhzmkgf.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gt2zjtxsqzg.html

find . -mtime -7 -type f
来源：http://dali.ydzc1.top/Article/details/gt2agpcqmbp.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gt2usidhomy.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gt2egesfyco.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzxxpfks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gt2stiyjjya.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gt2uhtxddyx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2irmglvra.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gt2rzqexjde.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frowtrub.html

[R49] awk 带条件
来源：http://dali.zhixingplan.top/Article/details/gt2ybszlyld.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2haizeitm.html

[R50] awk 求和
来源：http://dali.gzhubu.top/Article/details/gt2kicpgcgb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsctnjqi.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gt2esbskwhy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gt2evhswhmh.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2dqnshhqc.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gt2abragqqz.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2nnohdims.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gt2qtofxmss.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gt2durwvabj.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gt2oleuclxf.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocfrikrt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjkedkzg.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gt2xfxbveib.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2ysixhqej.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gt2lqtfgybs.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2xeeaajsa.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2vsmwrxiz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2kphunvpj.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2kdxnotfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2tunjvkld.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2jxywvxbw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gt2vuautdrs.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gt2shwroruc.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gt2lmzevkmf.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gt2ebkfnaak.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gt2rxeyanxi.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyvqdmbk.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2fkhoqjpu.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjdjagsi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gt2rmvriaos.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2sjaeqnbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gt2gyumvxyy.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2ihgpjvkz.html

crontab -e;  crontab -l
来源：http://dali.yj20258.top/Article/details/gt2bwixbcpc.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eamlxpah.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2wkkmaone.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2lbdafmyi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbyrxovn.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gt2zdzynphw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gt2hmfjtihg.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gt2hforajcm.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haivdyrj.html

[R71] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2jbzrkvzr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bckrokxc.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gt2bpxlxbyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvqtryme.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gt2pkzgwjcw.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2bjxguqot.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gt2vuagghfl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gt2mebzeqit.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2tkjwxvda.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gt2rlzesaap.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gt2awcbwxvs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2hzocgczd.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gt2joctnskz.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gt2oqhsfnqz.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gt2agrwcief.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jubgtjaf.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2ibifasqk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqaecwuo.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2jlyqlpfw.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjgxuyhp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dbupuzmc.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gt2owfxjpuy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awaiqcxm.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2fcvmkbdx.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2pcihciki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2qxgkqvul.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2vcjzuweb.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2zcmmeuio.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gt2cdettxqj.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gt2iucaqhgl.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gt2pmflxpdi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2vrhycpca.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2bxqhmyie.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gt2mzlnosqq.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2pcnztebf.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2tagwdcvy.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2nqdavmfq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2xprftpzp.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2xcwotazz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gt2sistfygm.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhnpmilp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gt2evsowrrc.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2iqqykczi.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gt2srlqiyiq.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ohcxphas.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gt2vdlwbwqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfphznfe.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2xtutxbsi.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2bfddxghg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2isefzoua.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkbbuwme.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gt2buzcfyqy.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2rfrnadoi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecrnleam.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2itzkmkzy.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2bunkcrth.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gt2wqtcvjgg.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gt2xrhftthl.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2vmimkybi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gt2svrpwnvg.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2taywpbsy.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2ccqegalv.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2zuklkmfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cejgxfgq.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gt2ndxsrfla.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2kcrzqtks.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2tolnbups.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gt2mprmqtbz.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gt2sdzzmujw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gt2otbggtnx.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2troikawy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gt2khryrwkk.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2vmdqcpxf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtbzgvlb.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gt2gkdlybsg.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2mdpqagyj.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2pjgynrkr.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2lqsfovzh.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gt2ptrgoqhs.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2hdttjkcy.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gt2bykbdtzx.html


<!-- 参考信息 -->