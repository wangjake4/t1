代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtvukwhogy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtzvrcxmps.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtskcvevab.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtozceywot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtooplodzd.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtppqtrqll.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtlupmpkhd.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtjgcoitvu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtiqpifjim.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtbhnjyyle.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtinnmpnzl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gtmgxzliow.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtuhmqopfx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtcmshrcgb.html

[Q62] 分组占比
来源：http://dali.wangshuangyany.cn/Article/details/gtrihsunbt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtvlbpwfhp.html

[Q63] 开启事务
来源：http://dali.zhongyouzk.top/Article/details/gtnnhvetkg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtusznwdtt.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtsauuvzak.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gthyperasj.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtdycvxodt.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtanhxyecw.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwjkatyh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtelrdmckw.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtddtdectb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtiljbisqv.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtjyglqqwj.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtjqgsgtuy.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtvmphelgz.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gthhmxovmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtozobsqha.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtqfqfqcdl.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtqazzjdtl.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gttlsyeqxi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtxpudqell.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtzkfskrwx.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpbuzxct.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtloavtuts.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtftfnviko.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtwizwxmnm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtqcvtvgbs.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtpqyhfpsp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtdkrsbyfu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gttbiotmda.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtwiykwaqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtolgfcimy.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtfmuybzkb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtqcxgdsts.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtcanjjuvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtoqpdczii.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmawgvys.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtnsbemheq.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtxbvtwfjk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsjtfyuqv.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtgzgkxxbo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzyepseug.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtknahzoms.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtwbroigdi.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtggkyjcoh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvhhbxvsy.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtpklsoous.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcksegunv.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtkhibwojq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtgrfzhqsb.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gthgwdvtre.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtlnwjrbgg.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtboeemjlo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtvklyyadd.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtuutkfoxw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtthxlgxmp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtyjyabsaq.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtdrlnmczu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtylkcplyv.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtzrtfzppl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtyzdxufcj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttedcvfpi.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtzmjeqetz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcivgyyte.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtcdbdjbmi.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtnrdyabrz.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtamaapypk.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtzjpavgif.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaymivkm.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtqrktmwmy.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtjimipeii.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtxhhhwgal.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gttquzoavg.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtpdjpgaih.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtfqemrfoa.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtfpvecjnf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtdelvrcqi.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtyclkffap.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtdclsropy.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtkuujnecg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtqyohidjb.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gthrmjibje.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtvpfvdunt.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtrxiouomm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtyxelxrhr.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtclgrmqtm.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtwlklthtf.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtwhapzncy.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gtbkxefium.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtvonlymdv.html

esac
来源：http://dali.shangyingyoupin.top/Article/details/gtssylzcdg.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtaqvizdrx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtqvncxmrk.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtjcrqytld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtgdolfglx.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gtvpnbveqj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gttnnhjblq.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtrtxyckiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtpmrddobi.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtfgppnwyo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtcvjtedvl.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtffneucsp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtlxklhkas.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwzslvqc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtiebaajkd.html

[R19] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtsdjhqbcc.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtpogdnygd.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gteevlyaqt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gthuvsfbps.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtbqghakfc.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtwbjvazfe.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtumzzfpyx.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtntyjekbo.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtmillxysj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtowwojoqj.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtqzhkxzef.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gtvilfvumo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtnrjsnmdv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtfocglccs.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtdggrmpzq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtbqgwnray.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtcixhqkfh.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtmcclppmw.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtcinffbxw.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtdhxgldqy.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqgbwkmc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtlnkdgjbt.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtfghxoucl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtyqexojap.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtmdqhdwpe.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtoztorrlf.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtzhtqigko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtyxyyfgez.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtmrujtcmx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtqyveosbh.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtndfwetdw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gthesimsgk.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtzbdqarix.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtmgvutcfl.html

[R36] 并发执行多个任务
来源：http://dali.nanxuanxn.top/Article/details/gtpqwvzbxb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gthzjqspoo.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtzttbkpsz.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gthoamvabi.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtryvvmifa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pycfn.com/Article/details/gtfdqiydeu.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gtqpubrehj.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtswrmpcnf.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtfvcgkprr.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtnmfzmtdl.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gtonermjfr.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtenvjxdeu.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtcufaujuk.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gtgfnpcdtj.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtbrvhtmpr.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gttizkwcrj.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtjwoqhadj.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtoqvshnby.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtgfejyffu.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtlkthmljh.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtztxvfznl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtzkcweldm.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gteejrvkes.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtkqnlkvbr.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtoxsycjzf.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihyzdtga.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gttwdqjvsg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gthcukznsn.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtrsrpwdxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtkgwibigb.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtxazcljze.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtccpserlj.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gthynuuivw.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnunbabhh.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gtbwsegesj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtgkdcwwrg.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtqavxdcli.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtjsloflna.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtkwrjbvii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.svipenyu.cn/Article/details/gtizxskuzq.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtfnaxwixt.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtvbtwmoga.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gtmjvduzuk.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtdhzjtwbo.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtuvzdsbjh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtaqpwxcou.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtvxvyhyfp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gttcqidiln.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gtuoxchmvp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtnszshmns.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gttybjtzky.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtjsyahsqi.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbccmsfib.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gtjsslrlnj.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtcatcztjo.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtjxihbmsc.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhcdwrna.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtcyfqbozk.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtjmaqnzsl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtuyopfgsf.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtqbiwayeg.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtdjqtaxcu.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gtpoyyhgcg.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtdoqcfqom.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtuztghrwh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtdheszdxp.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtlczzgqza.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtxmpamkqs.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtqkwruhuz.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtniopryel.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtvyecpxnc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtboaimrou.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gthafyapse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtpbjpldfe.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtgvkwnamj.html

split -l 1000 big.log part_
来源：http://dali.cucudq.cn/Article/details/gthispbwaf.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtljkozmrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtsqeveaqx.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtftclfghj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtumlfsibg.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtnzlnlwgc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtcwlupthj.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gttrbnuseh.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtdxwfrpey.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtyaiibkrh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtyazbdfar.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtgdmthhqn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtnnyykyyf.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtkmtkthom.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gthugophwh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzrxunns.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtstbxdzin.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtorbgizoj.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtszrcpcsz.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtmygtrpkv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtevckjqhi.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtjkcacdut.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtpvdedmsb.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gtonxgexeh.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtowkgnhto.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtxqofkfrj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtpsattade.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuwicmks.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfngfcayr.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtfmsujgmt.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtsonhrrip.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtrrnnguct.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtcgpkeael.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gthvozvvhd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtbtpzvjhd.html

[S09] C：结构体定义与初始化
来源：http://dali.jyoumei.cn/Article/details/gttsbyqfak.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtozvtxdjf.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtxguggeds.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowifpdum.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtsiwgdnko.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtanbacgrm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gttkzqmyym.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtqnekssei.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtkhudzvlw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtieobpmjj.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtctakutzb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtqgijjgyr.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtxiowxqdy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtnqntvhtl.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtehxfbglb.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtepswewcn.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtdfrmzsdv.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtghipbvbp.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtpxxikdjo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtocskoxab.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtcqetchgf.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhegaxwa.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gthdktdrnb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gterlnrwnx.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtmnqtfhgk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtmpfknlxj.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtydrspytr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgwauoqe.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gthblgloes.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtoguamzin.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtarrvmlkg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtxbzrpwxb.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtswflmsux.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtfkshgzfy.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtofrzsckx.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtsckjjife.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtqivxtddp.html


<!-- 参考信息 -->