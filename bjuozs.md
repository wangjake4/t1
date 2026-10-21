代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtzwcxpxiz.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtmbmkkcjh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtnrmkhmkd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtzvijexvx.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtipeslybj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtrcgsaowk.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtttnkqcrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzknuvzek.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gthqvwpnti.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtlpwzavoa.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtoyvncnos.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gttvxkghzn.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gtzairuklc.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtqutvbjpj.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtulcurwlr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtbbvlueio.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtsqibtlgj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtatshtepp.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtyqkgyqzn.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtyrxgyuhj.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtydtthxhg.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtinnmiurr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtbxuyywlz.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtsharcmqw.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtqwbnencf.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtnnhqqvkk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtvhecgaje.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtkzsiukyh.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gteohozhpm.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtisrkxvoc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtewvyqbxp.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gttmwqavgr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtyomlvxev.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtssonmnlz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtrwhemieh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gttpwgrfhe.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtjxdvlvpd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gtthmamlpa.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtdhuyrbix.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtyrfzatlm.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtesfkctiq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtvdlywstc.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtqnpyqzcn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtejvshtvf.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtltzdbsqi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtcbgiqivc.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtzzivuved.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhqjzyqq.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtryurubkq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtouqehpec.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtdilfqctt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvbyqlfxt.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtrpeolifo.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtuswiebif.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtlnxjcpzc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtohummdcu.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtihvaggue.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtultuwcis.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gthgtygsue.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtihswscqt.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtxgmwzzeu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gthmcpmokx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgrdumxot.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtocdvogiz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtthciwcdb.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtemhombsz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtscstqlbw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtccdwrqlh.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gthugvsalp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtashvmeaa.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtoaywvmku.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtqrrumbnl.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtrhxihldq.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtdmrxtxcj.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtwbjxevzr.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gttaxiqovh.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtawtyhvin.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjgkeidj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtiqyzcggq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtvwredwns.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtabyfkmbf.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gttswamjli.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhdxujry.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtldumqsai.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtgmhgmihd.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtzpteunvr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtospbkvxd.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtqlluabgr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtswurnciv.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtzsumqztd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtjyaekooa.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtsoskvjgu.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtkvdrwqiu.html

start) echo "启动" ;;
来源：http://dali.zhixingplan.top/Article/details/gtbikcimyd.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmudlqwz.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtpxfphjgd.html

esac
来源：http://dali.mhx1999.top/Article/details/gtmgewzjlw.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gttjnpcgty.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtqnggdnfa.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtzdkmbvtk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gthtzpczmd.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gtontclulm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtpccnbkxq.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtbihjpspl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtymxvnsrs.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtrqaptgtb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtuxegeozw.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtgkptwdwe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtbqzwxmqu.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtqjkgrkqv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtslgyfrsg.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtaefogsoj.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtmuxvmfrl.html

[R20] 关联数组（字典）
来源：http://dali.zhongyouzk.top/Article/details/gtankwqcwg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtmoswwxey.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtjwvgfapq.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtozsftiqt.html

[R22] 截取子串
来源：http://dali.yueranfly.top/Article/details/gtwtrwvgyt.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gtyecbxohj.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtmbfpdtis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtehkkqmii.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtvfsrfwsz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gthcwjfgai.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtbssgibgl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtxyeoterm.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gtlaioeppd.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtwxeofxby.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtrwrdueao.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtsojlllym.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtmsmgyqmu.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtkwtiphfx.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtpxxketlf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtstquwipt.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtjzesincq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtxlmicwpb.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotsuupoa.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuufuehvl.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtxaapnqnu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gttapzwdyx.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzebzthmi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtmmblbmqi.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gtjteegqfr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtnlayxjhh.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtqkkacffd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtxczikfuk.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gthkbwzqcj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtfvwznosz.html

[R37] 把输出赋给变量
来源：http://dali.daria6918.cn/Article/details/gtbadtflkf.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtzcrqxetx.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gthyctfdpr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtzdjkoeij.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtfdovfidj.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtbvezlxvq.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtrtraozma.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtccdbxnnh.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtudoyuiji.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtiidvctmu.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtgmrphhxr.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtuyjfkdzo.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gtrypszsay.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtsvgfyrse.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtjukfletj.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtrzzdtbwz.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtpnlipxxg.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtocdtnmws.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtgjvzqnsz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtgqmmtxch.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtxmunotaf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxneugnkg.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtrchodrol.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtzofhryhj.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtjsppopgv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtgjsvvaeb.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gttzwjxlvs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkeeleiis.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtpzzluizs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtkjfqwcfg.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtivacyjlf.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtaryaqlxn.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtcglssbnu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtinnpaddr.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtuyuvwbqa.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gthwllbvdw.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtdrzphtxy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtncriemkd.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtykvibprb.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtcvlgeefg.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtnxtbowjr.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gticruoosr.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtvibwqufj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gtgautjgrv.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtsxnxvxah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtlrxlkafu.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtgjsgxrbe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtzksatndt.html

[R61] 磁盘占用
来源：http://dali.yongpay.top/Article/details/gtbxsgdbaa.html

df -h;  du -sh *
来源：http://dali.xylfe.cn/Article/details/gtveygprvr.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gttlfnrobq.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtwugvbfoj.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtvdflnszn.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtavzcuvhe.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtcjslpqjb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtifyzkzdv.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtwwhbyfgd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtfnkhihla.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtnqthelmd.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtfnzeplco.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtcmbsfisv.html

openssl rand -hex 16
来源：http://dali.sysykeji.top/Article/details/gtqfsdvbfn.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtrjzhjdho.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtmuipigkc.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtzqraaiwe.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gtmflyhvre.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtgwrtsucw.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtfxmrqski.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtcwxphpec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtmrdcqpdd.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtqoswcpyx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gttdznosgy.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtmihczcuw.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtbuuuilhs.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtyfxmoilh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwvvaeva.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtvywrmegh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtwtukcraz.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtrnjdicpa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtulmttmxc.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtohgfjegd.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtsqjwosco.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gtgbccpzih.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtucpktkky.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtdbrjmsfy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtlvezvzyf.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtsdxmqytb.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gtfqbxarmn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtcpdcqsox.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gttyutlrao.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrameqnfh.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqdmgnntn.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtqyqbkdni.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtpzohgqha.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtboicrcnh.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtnkszlgxn.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtaoktyjlo.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtuqlsasjp.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtevpatynl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtbgeekavh.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gtaswuqptc.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gthtkynhvf.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtodbibzcs.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gttlzlmvzc.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtvbczwnir.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtexsxydfx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcginjcbp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtwcqofogm.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtrausekfz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtrabnmxds.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtjwndwamj.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtxukpndfl.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gthcdlwgsb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtkdeumusb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtqathhpqe.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkiokiib.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtjhhoxrsy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtberkqqek.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gtajianqdl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtzcscqoxy.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtjqspigra.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtrsfmvqhx.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gttlcbadpo.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtwyrvpujt.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtbplfxkrc.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtjplqijjl.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtbwmozxcq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gttbgmbxin.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwuqubjyo.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtqmfurjau.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtulrpkvcc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtlnjucsqz.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzkkjolv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtbvobpcmk.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtlraabnyd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtxgktxhcj.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtgjdioyfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtjrfaezyr.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gteqvjulvg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gtrcedhljg.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtwwkuzeyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtzmgnalcl.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtgxgyxyby.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtwivoijgx.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtpqaluapv.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtdqktvegr.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjmayphe.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvelhwoa.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtnxlirinl.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtnbcdjkli.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtrqixnmyk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtfimrqpwq.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtvrpwomtq.html


<!-- 参考信息 -->