代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtufbkbofd.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtulflxmyx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtxenbppqi.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gttqscvxbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtqceoflef.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzwllboo.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtnywmsnlv.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtwjnhtamx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtjgyizkon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtervkrftv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtiiaikxqw.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtztbuywtd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtpcotvrnu.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtkdcfetej.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoakwolyj.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtakdrfoav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gthyschhjq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtoihwemlc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtzypuzzdx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgtjsach.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtaikratxj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gteyvzwltr.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtyselkuxq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqevjxry.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmsixhla.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtnfyqucnh.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtircgsrkx.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gttolahusy.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtuenugbhc.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtfoekfipu.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtfdqlynhy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtmjbvawqs.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gthyoqfmad.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtdosbphwl.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtxytjvqkc.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtoqrhsxhi.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtizporvbg.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtbdwmchzi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtcnkgdhhz.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtzujzsvtx.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtdimnglpn.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtmqegpsxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtlruyxocn.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtgbyvajpi.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtlmykquzo.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtennejrho.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtpizzidvx.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvrqroxs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtyqwoufce.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtsrmrcsdq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtgfnmhgpa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtsrjzbmib.html

[Q76] 按天统计
来源：http://dali.sysykeji.top/Article/details/gtfszyqdfo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtylgxbibd.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtrqrajaps.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gttlrqbeqq.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gthfogokvp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gteavfzsqc.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtxdkcmqwx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtxamjuqzr.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtcbopeagz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtsiuyljls.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gttpfguzbl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtlhwiielt.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshpmabsk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtdhxuxitj.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtuvoufzsl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtrtqeawgh.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gtexapzaee.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtdgpwvjhx.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtrjxqgwsy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtxipiwuhj.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtbmuvvvfw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtziqkcjwj.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtuzctrmpe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtnxthkvwq.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtyugqlepb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gttasrmwnr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gtjzucuodh.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gtaafhwhpt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gthkwdihuh.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtuayokrtl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtcrvzlhro.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxlrbvbcu.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtfwqbjfap.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrrnmjuqv.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtvfzurupj.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtfywianma.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gtmftqawgj.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtvdevwtik.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtjggmswiy.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtvcpvlkoz.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtgfqufkdb.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtweytuhfr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtuaqmquzx.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gtawqszogj.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtxqciknlv.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtodflcwev.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtylchsemt.html

[R07] if 判断文件
来源：http://dali.hammf.cn/Article/details/gtzbirldot.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtgcsfbhmm.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gtmukbdaer.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gtnwmamhey.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtuefdfgpe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtxhsfsxyi.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtedxyfhgi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtpaagzndi.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gthllpgvqa.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtdyljmlxc.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtljefampl.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtszvowpvx.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtqucpsmnk.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtnzxszitx.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtmpdynunm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gttqmesmiz.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gthzkrehhh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtyvthfzss.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtestmwdjt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawquaks.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnaxsmrly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtratgfgas.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtugwrzyze.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtykxoqcow.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gttpqpubou.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtsboipwnm.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmdwatvk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gtwtkzidfq.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtuoshemmb.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gttjrwpyes.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtexjpemsx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.iojbl.cn/Article/details/gtgzhjxalk.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtbcaasmbq.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtyzyajjrt.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtnhebgikp.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtswzktsex.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtbjrqtzuy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqxgpzix.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtmowigtxd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtnysjvuoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtjyijgndo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtzkivdjlv.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtskrfayhj.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gthmxpldyo.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtmqaydyrx.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gtfdbytfxs.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtvptbguhd.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtehvqyigx.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtdovqvusm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gtpxjjpufk.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtzirncjoh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtjhicnzuq.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gtixjkuhnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtyawcyzlm.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtfwlpkzww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcnbldpff.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtrbqowjuw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtftraslha.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtbtumrqat.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtedqonkxo.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtbvrxqckd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtkwnhqcfk.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxqjtyvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtgqhctmdn.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtkdkswkkr.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrshqhfbp.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtrrrqmxpp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gtkcasdnql.html

[R39] 重定向标准输出与错误
来源：http://dali.guowangkeji.top/Article/details/gtoouhosdo.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtwojcuwfj.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtbnvdqvxd.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtovemjkfr.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtdirsoghi.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtgritetrs.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmamyran.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtuwjjvahp.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gttqjekmcs.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gtotpwbujg.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtxkegnxgg.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtbogtstjc.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtbttknoje.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtdrovbtpj.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtkqzripsu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtfifvyyxq.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtnhqxdega.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtwohuhbtt.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtqyqazivn.html

awk '{print $1, $3}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtcznorffp.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtucpysvfu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtcjtrtmxj.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqedcxkmr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtirazojkr.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gttrywzlov.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guowangkeji.top/Article/details/gtiaablozu.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcdrlvkc.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtjdjizcle.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtuggcpuen.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gttzltqayw.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gtclukyxql.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtfnxpfqoo.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtjvkpdbio.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtvjixbdbq.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gttcstxvsu.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtsivlpoqd.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtpzmxdihx.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtmrlauwom.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwvouxqy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtopuwdpjv.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtnmggjwxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gtwmszzawb.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtikcfpcag.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapswumuo.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtmhmfldzv.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtbqfehwht.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtsmjnvvwt.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtqkdcvbue.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtpbqnsrti.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtgcmpcknz.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtlkkicfzm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtifhkvjnh.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtzwcqbyqc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gttcqqleeh.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtloamzvoa.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtzwilrzqq.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gteocddjda.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtwumehnmh.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqqtiscn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gtskajqbol.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtyxhvebux.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtoalgnatt.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtrekiqqdg.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtplmrntiv.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtzvhkbdsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gtfcekpebd.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtppnchcvb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtalyxfcdn.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtonrjihih.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gthkrlmnmx.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtsequonxt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjgegntjn.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gtbaxjxqza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtppucpnpc.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtakoexmym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gteuvptchk.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtghtpymvz.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtxcraklik.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtugizqufm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtscuzdoew.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtsnofnyqg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtysuthlvh.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsdgybvw.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtsqbqbuli.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqsgdzunz.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gthmknzpjr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfdzsczjw.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtclogzjci.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtndhjtipw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtbngxistf.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoddsiusd.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtmczlixmf.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtpcjhukmv.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtdjcxvuav.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gthxziefsc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtumbzkmff.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtpvmgddyk.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtwkjdoewa.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtbzettdhr.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtifbfvfbu.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtbzoldrvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtalymxaqs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtdyzgwjln.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtqzyhxjuh.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gttflescch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtbkxwchqv.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtvghvufsy.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtoefmrpux.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtunvurcyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtvhfewkwe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtctedecoa.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtiwogvdoe.html

[S12] C：写文件
来源：http://dali.sxryk.cn/Article/details/gtkceicsfi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtbfpifsjz.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gthezfpcxv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtooixkqzz.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtyqutpdpk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gttkdylnbw.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtnwnpeqjv.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtviwygbsh.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gtyqqeccao.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtlsovdvxw.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtalgzqisz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtegvlvwfx.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtjjdpmdeq.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthkaozpy.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtmjjewaso.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtojxgrkfm.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtwygcvcjp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtyflyqcum.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtaynelrms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtlghrejjy.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gthimzpxdh.html


<!-- 参考信息 -->