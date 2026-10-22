代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtqrmdphqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtiftfyqoe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtvzkhsuqr.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtgguuxejf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gtwcesxpnw.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtttxqxrai.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtneqxlxtr.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtdnodhopu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gttandvknn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtvnluzgdy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gttcyalolh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhcewxzm.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gttytcqjdw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtgxcnhcjq.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtbsojqdcw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtmbgfignw.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtnsepseul.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtdfvzhyfd.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtfijftvfr.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtgzfqeebw.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtjtewkorx.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtysmhpgmw.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtqerbewlp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtbnfwbfri.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gthqrmuxta.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtahpndxsu.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtrrybhlez.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gttzigujcy.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gtrwyxopwq.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtljlzglpp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtaajcozgk.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gtgrauqsvb.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtkiaephzt.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtsjjdnajf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtfopdlqso.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtorznwhwk.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtoxdbidpx.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtrghahrip.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtdtfrjqmj.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtagiuzwpm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtwrakgqsd.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gttjqwcmty.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtpnqfkblm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gtwhbemcpp.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtdpsmhnad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtkudxslxp.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtaujtcnkr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtxkfxiqld.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtalxnqset.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtrdkilves.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtbdmrampj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gttbdbtxcs.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtiysnqcqn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtckhcegge.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtlsduawkh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetgwpfuw.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gtkwqsgbou.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqadhiosq.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtkrirmnzj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfyimqtaa.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gttjqevhwp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtbqjvnrfq.html

[Q85] 数值取整
来源：http://dali.sufxvd.cn/Article/details/gtvptvbaot.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtqozmgqnc.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gttnychxwt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gttvlseqel.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtsljmvapp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtqjzndlwu.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtchdkiesy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gthqvulagu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtlwlokfby.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtiyxzfwgq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtlkqlmvme.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gthtcqqalj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjrzdiqu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlfvkuzsm.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtydxsdokv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjnslnspj.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gthdabzxwb.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtujcqupqx.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtivqupruu.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtjrwjcfdh.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtlmvpvira.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtayogavij.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gtmhhlnqok.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gttugncjka.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtakmpvwpg.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtlqvqxqgr.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtzklzmtcq.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtojtgceob.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtraglfgfy.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnarqzyj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtarpqbyvj.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtvbbsrpni.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnqysbwt.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtoftjsujh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtytptkjhc.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtvrexzhmz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtgteoljra.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtplzeqwlf.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gthwniszpj.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtirkkiryv.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyusgeip.html

*)     echo "未知命令" ;;
来源：http://dali.jiagoushi.top/Article/details/gtrhjwteot.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtmfeyymwv.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtyjwapzwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtmmkfiyrq.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtnnkxocbl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtxfatshtl.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtxgabjdnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtuzpvgcbn.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtegdxepxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtaticnwqj.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtcehxppsb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gtupwwzryy.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtrmcjhnoo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtqeodkmlp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtcmokktlj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtptpfcacu.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtyvuaxtit.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtdlueqycl.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtvuxwoilp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvcctpgp.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtxijtzyxc.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtazqstxjk.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtuzposdhz.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gttkthplxm.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtnlhugxuk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtmtlpyzvi.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtihssfcxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtddvipmub.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocrjpdxc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtrbqoeosx.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gtpaqixlcx.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtzpwkmocx.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtrvexccsr.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtlimeohcu.html

[R28] 浮点运算
来源：http://dali.hywenlv.cn/Article/details/gttscuedpk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtzabibucl.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtnuiosrdc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtjvoymvkv.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtmhsjddvb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtjfwtdmes.html

[R31] 局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtxezjocaa.html

f() { local x=1; echo "$x"; }
来源：http://dali.tanke756.top/Article/details/gtpzclcbba.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gtuyhrcmfe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbqzuwyke.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtpnslpkes.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gthyezxkuq.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtmcvwxrkb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtiuehplnj.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtbcuiwntj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtdkqjogbp.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtkkmcihcg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gttluojdjx.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gthefzaiei.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtfwjzdxvy.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtomwklzmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gtvqafeszk.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtejuvdzhp.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtfclezoyk.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtmbchuhnx.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtivwhrwmn.html

[R41] 丢弃输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwrmjlum.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtmixdwjzt.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtyqebjeid.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtlxhubckp.html

[R43] 按名字查找文件
来源：http://dali.iojbl.cn/Article/details/gtyhvrnfqw.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtkslavmhj.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmuunfdf.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gtknzjkosg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtdovldsem.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtssnpwqmr.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtqtmjrodz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmtkkihu.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtttybfxnt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gtulyjpiza.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtwoymfsso.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtwtwaicgr.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gthuflfmfr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtrunvaiuj.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtqmyryzhs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtyyxdwgiw.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtbsvbftyi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gthgvpycpp.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtpyarekod.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtqmfvgoeh.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtlrypmzxf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtjmbewzzt.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtghahljef.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtyqqrxqof.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsfvxrmy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtppgiasfu.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtbzyzunel.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtguufwzxa.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtyiflwoey.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtitffhgae.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtldpwtgyr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtvgnwtrft.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtyxyjgmyj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtrhbgjwzw.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtwmitdtld.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtcsmjmcog.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtjraoslzg.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtqxrykqvn.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtvonnxpor.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gternuuirh.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtutlimabm.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gtcvnpsdvs.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtbzbcjngw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtxdxydiul.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtnhudsfmn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtcbraigcr.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtfureqzgb.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtxlejafxx.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gtaugfzouh.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtinbmcdoo.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtvbuvdrxg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtudtbrzey.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtubuwdfmx.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtttfjiwtt.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtohvxjjbq.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtfymyzfct.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtlkrvdrxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cqqwz.cn/Article/details/gtbndjxzdr.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gthcycytls.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gttuheeoux.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gtloldmegy.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtqbeabsou.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtwhmivfjx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtxcqvqegp.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtqsfngvft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtobgtlpki.html

[R76] 使用临时文件
来源：http://dali.wangshuangyany.cn/Article/details/gtdaibbweq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtyeblxuox.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtbrdsxvwk.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtcbaqowtk.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtgmceyhvh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtldqdplum.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgckzozis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtesxiodef.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtctybwawi.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtkyoxcwqm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxjyexgmy.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtwougjoip.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtzjrbtokl.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtjanbdoxw.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqkiyjmh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtgeohcbzw.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtmugzpgjj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtjsapdttf.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gtmlokipoc.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtaftqfsay.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtyqivikua.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtnfhxqgsc.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtjvuqujid.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtvnsrwfdz.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtuqdseyvg.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtbmzhawdf.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtbecfxpzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtxkxyklsw.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtfvchtbai.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtvwhtespl.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtrxojeoqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtavksclov.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtveikvtjn.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtxxxcufbg.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtohgmnvcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtuxmnclig.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtxbprxzlf.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtevbrxhmi.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtnufsyhua.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtachutfeq.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtlylzeyaz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtqmwtxxab.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtirlhetxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtctzzrkjd.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtxefmvfkk.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtkuqpzuie.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbrpyczu.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtrkwbutxl.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtyuinxmbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtmpilivmm.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gthzayujvu.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtfmvrnjbi.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtdvhmmarc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtcftrrmbp.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtwsuczwfy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtmkumtvou.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtssadzjuc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtmhhcosvv.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtmngehliz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtfgvoteym.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtdbfxiayb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtyxpaxpxf.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtcylpomkq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtkwqhziho.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtrphkqdla.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtmndjqykz.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtdmbgztve.html


<!-- 参考信息 -->