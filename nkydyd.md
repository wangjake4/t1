代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtmypumokn.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtkoppvcro.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtosiqjxwk.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtvnmbyfke.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtoytjfjgt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtnyrayfbo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtlfkldcyx.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtlmjkjdqe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtffqrsrfn.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtccanuhqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtibpkyuyu.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtytgiczlw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtgvxbzuog.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtydujjewj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtmebogzhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtxrvwlgfy.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gthqjrxwce.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtzjlisowg.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtcjbnepbu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gttegkjuer.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtbtlcnjdc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gttjfbbfip.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtkwbmhepr.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtxqfcmbve.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gttrgzvcxx.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtsnnkkekb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gtsxwdgkvp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gtssgsyzyj.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtjsxwvntf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtzobgscri.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtypddmdgp.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtpgoeghcr.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtigyndnwi.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gtkcirevvl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gtlhbswbkv.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtbuifmajo.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtpisjgwac.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtmzdewkel.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtkllrbaoq.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtfubnbxub.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtutdfrfmc.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtiwlpffyn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtlvppvdpw.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gttynqatcf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtoerqbyrd.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtghbongnx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtpudlvwzn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtjgngxhbl.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gtvqgdaucc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtvvyekcue.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtgfqdvztz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtrrodhcsy.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtenagkice.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtdrmbdxku.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfioxcptg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtpsloxsbs.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtodeverpq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtuyncdbfo.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gttvrtncty.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtoijgetye.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtxayqmcif.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtqdcrgimk.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtpriifiek.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbxmnnbhs.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gttjapqmxn.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpsehayte.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtxrdpssmj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtqzedkocs.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtyapivrar.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtwgnvozwp.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtllepfrec.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtgcpsmwrg.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtrwlzzxon.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gthbyudnhx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfamdsac.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gttzjjgfjw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtvdqgtwwd.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtqqzkglcp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtptrrfbnk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtctdtvtuw.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gthdrzzzdp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpyacxgyv.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtohmigkzf.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtjdhivbzz.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gttufqvwgz.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtpepemjgz.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtjoykipoe.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gthwptuwwe.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtruaauizl.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtxhxkoxhp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtfgovlczc.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtqootjfgn.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtuwlrcvee.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtstsoydsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtobnjvyqq.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtigpfjcpw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gtuuukxuzk.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtakgrxkxl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtzpttifvz.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtlunrnusl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtbfoywvvo.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtlkdulxkm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtvtywxgiy.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gthtusmmsd.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtxdhpjyah.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gterivdkzc.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gtissrfluv.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtdvyxtpdw.html

esac
来源：http://dali.shuidangran.top/Article/details/gtngxaldxd.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gtxcoslomd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtrzccamqh.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtrksdlvte.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtkvlitslc.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtjkkpdeif.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtezzudhof.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtzkmvkjhe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtpfykcjyf.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtpevubzph.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyvqwnpl.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtqtjeehrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtmhovuxok.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtfenihizg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtkbqoryrs.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtvmbllmoi.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtgpgbrvpv.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtusttzfnv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtjxthlwil.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtoyicusse.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtnbyvvziv.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtiorfqikw.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gteyjltqvc.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtazhezryp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtnfethhfx.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtjekcbqyz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtwbkdfaho.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtyejxcuoo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtqgqjyato.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtfcpiyxzs.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gtaqyjkjwj.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gtoflupfpv.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtvelwuykf.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtqsxbsbyj.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtvfoxzfcg.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtolhqguty.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtuqgsuqmq.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtmdpokucj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtupcprpni.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtzecrdntn.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtvifclrwm.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtjpbjklkl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtnwgsnugg.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtxkzfkmre.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtgjrrizqq.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtkfuvaxma.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtcwlpvorr.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtjcpoudvs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtqjvhmmri.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtlkprjfgp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gtxnzjqsit.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtgnlwftyl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtduyanvjq.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtrjhmheka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtvlktjfau.html

[R39] 重定向标准输出与错误
来源：http://dali.haohaochexian.top/Article/details/gtasnteitw.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtqhiktofa.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtjuilpbar.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtsuiqhpia.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtgigecdfo.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtnqeytfyh.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gtckktcaxu.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtbihcjisf.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gthrkduvxl.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtrxpwdzus.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtuvitfhvd.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtaehpwosb.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvayhjol.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtzpgmcwse.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtfwikejmx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtjuisnghv.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtvqchuzqc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssefhapd.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gtybheypvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtrlosrraw.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtyakulcxf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gteflxrgrb.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gthraqhdlw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtckkhkdut.html

[R51] 排序去重取前几
来源：http://dali.bjfxy.top/Article/details/gtiwagxrcv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtfomroknp.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtloqidogk.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gthctwoctp.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gtpgwcvjqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtwvaonckg.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtgruyzrcp.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtccvgxnxf.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtgwbmagok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtapcgbruw.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gtzfxpupfb.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsiqmlev.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gttfhbazcv.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtnxpvwzyw.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtnlztphyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtuazjqrmq.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtassvbzgh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtqxpdtsky.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtgcrepsha.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtpruvqijh.html

[R61] 磁盘占用
来源：http://dali.smart0.xyz/Article/details/gttnangkax.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gtgjlmtwjd.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtjbfyzgqs.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtdfboqzgp.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtpfuihvtp.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtessukmro.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtsmlcgjkp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtshtxuoph.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtkcpsowzr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtlvllvinf.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gteamhpque.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtypayvpzi.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvofiveo.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gthoryjgtd.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtocneknoa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtqjqdtmsj.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtryewkovd.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gthoswrzyx.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtqwfuoxls.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gtljabzlqd.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtyrliztvv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtgksztuwr.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtcikoinke.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtkcqxxbgo.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtyadwwwkr.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtipriybog.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtvhvzpgtf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtovxvoxkg.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtsgtsamay.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtjisfjevd.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gttpfbtsif.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtqscfgzht.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtytxvposs.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtbekmkmqj.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtjeiaismp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtvqbbozyi.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtlharaamk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtczfumthq.html

[R80] 查看脚本执行耗时
来源：http://dali.yangfankeji.com/Article/details/gtflclzwoy.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtuxlbjqal.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttagbypdv.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtkfestdra.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtafxjtbwk.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtulgfvpqh.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtjtfhtzhl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gttfuqzksd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtyuswrszj.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gttgqzhgby.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtsfeklkwr.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gthsqqglqr.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtwlyxwuhg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtoazilsxu.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtumhuvizs.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtecigjsqb.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtuloavbdd.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtsamldhbh.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtljspdrfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldscpjci.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtrwnmirrs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtszfzxqok.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaahpoxs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzcdacxb.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtzhbohtqz.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtmguxgkhi.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtbpxtbnvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtjjulrahe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtgtlqwzoe.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtktzkaemp.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gthfjiziyc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtvvyltkal.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtxewtpysv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtfybyxyvd.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gtmbazlkns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtzxitrwpa.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtcpfmeeid.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtxhuhxhcv.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtlulsetad.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gteowwowld.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtavttxbsv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtvmprymoq.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtlhkikqrf.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtcsjwuoqc.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtozvhxmvt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtygaesxkf.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtqcsyjyle.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtcclhzqev.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsylqzojz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtbbiqynxr.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtfnqbqaqm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtopymtjkn.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtaurjpais.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtitkptazk.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtdmrbxnvu.html


<!-- 参考信息 -->