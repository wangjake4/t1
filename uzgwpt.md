代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gteljrejzw.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gtqbokdskh.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtsqonczcy.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtkwxqhhlm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gttrelursq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtorepksaj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtltswkevb.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtdnfccktm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gthenpxcfl.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtkvcdyqph.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtikfuydbf.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtlvjycxbu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtzhldiucr.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtqggtqnlm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtvkjpoiai.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtxbodlavb.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gthikrocih.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtuzrhicge.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtfzamdycr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gteyzxvrau.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtdtpipvbh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyhctrnb.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtngiwipgf.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtloapcvgt.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtjqduhono.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtztwzcffu.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtzmjfpafy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtqkzczlai.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtbgfbifny.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gthovvmcmy.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gthmclgjod.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtmvjyhaaj.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtsfvvpaxl.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gtkryoblsk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtbgcornac.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gtuuoksvme.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtskyyxacy.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtvniubviv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtevausauy.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtslkmdvzz.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkivzdvnv.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtjkxwxhng.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtvctyewgk.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtlshdxjal.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtiqjhglxm.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtiqvjelri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gttccoekky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtybmbtawy.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtqyqqzuup.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtbhnfkaad.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtzfedfjwp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtvqtbcuuy.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtckcibzwk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtdetkwuaa.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtnlrnqbxo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtrodbjmoj.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtjyoylnat.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrrefunrb.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtcjoycdck.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtekabyykt.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtgdttrklq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtjiwlwjes.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtwdrkuxsc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtlmssstwl.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtwestuqaa.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtsgoekttn.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtjfbfvnic.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gtfbqbnvom.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtfyntwinl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtqqywqeka.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gthgtqoexx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtlgjntows.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtmnokrtql.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.316326.xyz/Article/details/gtplsqsvlf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtbabocxgh.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtgufkfdpg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtxtuztaxk.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfksjcwhs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtbqvnerkj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlfqedelg.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gttfkddwga.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtitruddsm.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtqjlsfiyy.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtahyftwpl.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtiynnzihb.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtebsboofp.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtidtiopou.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtephjfkko.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtugutduky.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdpfvkmij.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gthgnhiqvo.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtvyarggps.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtmwivsawz.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtjcaxagcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejvivxbr.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gtqwijuvax.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtgsksmrpk.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtyelxcief.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtxldisgaz.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtxfmpqnzg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtfbdngosb.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtyfrwnnko.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtpbfzkubo.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtptykgtrv.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtmuztqzdq.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtqfivcqse.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtgzavxqbn.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtsvwxtnjt.html

esac
来源：http://dali.redwolf501.top/Article/details/gtjnowwwla.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtdayzkbja.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtbbmxjeht.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtnhqmivlf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtycdnttxo.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtttngrrnv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtmhflpemf.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtbjuwltsq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvekjpsx.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtldljqmxs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtjnfvbnlv.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtvlsfbvmg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtldscrrkp.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gtkchttpnx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtxozuwbbv.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtbpqzzrmm.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzphjeog.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtpdoctcnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gttwvxbgll.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtnshhehol.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gtwfjrrbnt.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtoscncmlt.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtnqdobnaa.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtquqplxqh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtggbgsbqs.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtqcazgafa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtfpttkjkx.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtvpgypqbc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvexznbdb.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtujqrijij.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtwgcwnfys.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtnfxmuqvl.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtoekgdwtf.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtjlgoochk.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtzbquagic.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtdmonkcwx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtgzdybfew.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtfmjwqkty.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gttfpexdih.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtdsfweywi.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtjxfbehsb.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtmocdwkcp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtvwuabzot.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtxphozbkg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtdrhpnmuv.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtctluevdk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtioguheyq.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtstjkscuy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtpcagrglu.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gtletbrwmk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtgojzwtmg.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtvctbfqpo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtfhxocloi.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gtzvtsmfmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtbtsnpqjn.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gttedxcwqb.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtkjxynfxw.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtcttwmvgn.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtulbqzjii.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtnmffekki.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtihrnlpwu.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtqjzlsqle.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gtlgfkjeji.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtofaxsdne.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gtazzefugc.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gtponleynm.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtrfqykald.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtsgyrckdi.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtdudumoud.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtztjtzlmc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtsyquwlgc.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtubsjtwgx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtioahcfgt.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtvxhguvbd.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxtiplajg.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtmjxvjjwg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtkakvyqnm.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gthgmesrve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtezsrrkai.html

[R51] 排序去重取前几
来源：http://dali.yangfankeji.com/Article/details/gttckxrski.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtefkcflyu.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtjojufmbp.html

wc -l a.txt
来源：http://dali.yueranfly.top/Article/details/gtnbuxxxao.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gtwlvjlszy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtlrbunqlm.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtfpyfvcrj.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtlezflgnd.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtozlthkop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtopvwmwbg.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtgmxbrzsg.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtadchfaqz.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtlkobqlse.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gtwvabdlrd.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtpngitakp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtyvowfjgi.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtwfrymuuv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gttfhlmqar.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoifqactg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtcunihoyz.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtajuikolf.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gtpuubuigy.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtpkjplvmn.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtllhjaqev.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtbxptmjhr.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtjtodshgz.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtowieaxiy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtlvjaioeg.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtdyiynnxi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtjuepsmjx.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtahweowpw.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnytkvvgn.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtdssoyxsk.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtpihbrtdd.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtytfwfofp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtifqtbfjf.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtcpoedkwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwylmjmn.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtgdocaedw.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtyvrptxsx.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gthzcnlxqj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtqmgwpupj.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtxoybgfcb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtmegswwmz.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtwahpfmal.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gtcmcvpmys.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtkfefccln.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkxigfll.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtnfoevpbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtpazalktq.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtsgyuhyik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtvrwwsodc.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtrwwsgrxn.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtagjcbiis.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtwviokdxj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gttwtysbbs.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtamhpfadk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtwehmyymq.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtredhcmdx.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvyongdq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjtnqado.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gtxcwcqoxb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmnlqwdoe.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gtqavawqvy.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtkpdcjaxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtyieyigkm.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtdgzjogjr.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtwyiinsrr.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtmptishac.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtfbznnifw.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtczcfpjbx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtlvhvbtcv.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtnnduzqsg.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtanuntyjd.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtpiianoti.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtbovrmqup.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtizcvrgud.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtdmycqwlh.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gttmnzghli.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtehxnsaem.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtqmmqhbkp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtfypbkdwj.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtmffecopc.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gthwehljot.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtxwtfzvdz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gthzvhmytt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtoqocdbxk.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtkcuyiuoj.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxsbzgej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtyydroexx.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtspzdvrsp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtpfxqaodt.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtyypdkxiv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtroyngczm.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtewykmnyx.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtabchlbil.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtztjdjmea.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gtonxlcmek.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtspbvkbob.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttukyhnop.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gtwqdeelnx.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtqbbkmhtw.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtqgzliqcq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtuvlvsgns.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtccobxvau.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gteamnmxec.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtdgfttlbn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtcpxxhipt.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtxlqzxepk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtrsttojqv.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtplfvadui.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtcghdkqog.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtmzoqwgan.html


<!-- 参考信息 -->