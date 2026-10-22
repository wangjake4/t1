代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2edfjiuek.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gt2qqmkxmfr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2fefmfxxr.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2xmoqtspv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2qlbryxvp.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gt2bkehlfjn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzeenycn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2urthmrej.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttxdfpjg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2biavrcud.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gt2unakneyj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2brivvnek.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gt2niopxiqr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2lrxjqvpj.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2geloiknx.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gt2gzbrfsuo.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gt2azmscall.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2qycqqhgm.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gt2osnocuca.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gt2wyeoqomx.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2dijewzml.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gt2qnhnhnzd.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2sbzpydul.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2ycmmdrdd.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2ofrtikeb.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gt2opygxwfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gt2erefclml.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2jbpflkkp.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gt2kauiraqt.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnzygkjv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2oxtnhjfo.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2hotlbkmc.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gt2aznuquas.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkwibwrv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2znymhxut.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gt2mhmtjhrv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gt2zkiijloh.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2oduwgdks.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2klqokyrr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gt2qzxmpdcn.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2laykipvo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2dxazccat.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2yipkjibe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2xjtvxjci.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2xvhxqlzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsvfrtay.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyiehbjf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gt2qwnmyxul.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpsxpgqj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ezmmzknc.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2tvaytrwv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2uxrwyhus.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyfjymjt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mrqjfqkp.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2wgtnikak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2tyuuawve.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2ahwmhkki.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ctejtfqo.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llaeuige.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gt2lmwsbkso.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gt2tdazzgbs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gt2mgzsvxst.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2uewknvef.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gt2xixvivqw.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2kzsxyozm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvkkqosq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gt2xuvvyurj.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gt2ngbrakip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2wcjzdckm.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2pmrjujkw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gt2pebqiwqt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2sbdnvodv.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2yqppfjfv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xbabqqkc.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gt2bwcueptl.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbewltov.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gt2dytpcszy.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gt2xluqgyia.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2lskikccx.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gt2qafcujer.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2ypguztwz.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gt2bmfalasp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gt2zowslmwp.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2huimjaqo.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gt2rfblniwr.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2svggrkxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2gxqdlvyd.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gt2nhhgjbvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gt2ljtpezxu.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gt2jqoockul.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gt2zaghqwnt.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2olxkkhqu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gt2zkogwaqd.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2bvaekidw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gt2ssdmbaag.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2zejdqmni.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2acjhwjno.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2bzeaypyw.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2bhilykzl.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2ldxswpra.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcdnssrw.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gt2trajbpxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gt2tweqhaor.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2cojkzdwg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2vzmtyszv.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2ovrytfhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2trumvgmd.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajovnjgk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zdqjudy.top/Article/details/gt2gmuzkrox.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2hwyhinxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2qfeyjoki.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2ssphumnz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gt2lbkrrtis.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2qlqgfueq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ezuxcexy.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2zoeyiuek.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gt2iqaguxdf.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2ffcphilh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gt2tyctfhtk.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2hyxpbtlw.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gt2ptnwbkxb.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2mbkvtywl.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2giewplpk.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwszyrkg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wncefnml.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2enzgltfs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gt2cqegbejn.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gt2dojirpoj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2bxnlyvov.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gt2coolvssp.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2kdvgltju.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcjamkph.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpxxshya.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2onhaibxl.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gt2xxqjdcsd.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmtwhwef.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdbholzw.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gt2oidwdkox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uddtwuxy.html

[R31] 局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2wxpczgtq.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gt2jemlshfn.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2wlhyqfth.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2ryerzurn.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gt2wgjqtyoa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.birdmap.top/Article/details/gt2ocfjgnrw.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gt2kkujwxox.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2vqtkyypf.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2ihlfazga.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gt2scjytbvc.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmvliwcy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2jhodapum.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gt2errrtcxj.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2bhyuiqxe.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gt2wqexfuer.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2usqzjbot.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gt2gsfufbqa.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2nmepbyqe.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbyofvhb.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2rgvudnww.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gt2vqdpcgkl.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yromqsqu.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2mnceamog.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gt2vcevplhd.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ayafumiv.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gt2iyodsruj.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2geamcsrc.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohydjveb.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gt2esjzyack.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gt2ygeyfhkd.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2wkkrazpu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gt2yopxbppi.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2qhkradcz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2wjkgropf.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2tpgegcvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2atbavpsc.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gt2ffhjerzx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gt2bccasiko.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gt2vxclwugj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2oqfygptm.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gt2ibddwqit.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gt2cplqamvx.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gt2esnuxhdj.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2qmkfbmsm.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gt2tjjtgega.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.vqdsnc.cn/Article/details/gt2ryvwkbtc.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2fgrybvvu.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjjogchy.html

[R55] 压缩与解压
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnnatjja.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2ophrigid.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gt2tcuqakyu.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gt2szdvklji.html

[R57] 远程执行命令
来源：http://dali.aizwys.cn/Article/details/gt2gcxdjpav.html

ssh user@host 'uptime'
来源：http://dali.c1oappe.top/Article/details/gt2utjgpxsh.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gt2rxqmdkah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gt2vpgsposf.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2ljbwxjmm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gt2hsvejhdk.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2qeultbsd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2uguvduyo.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gt2spzmsgsy.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2gxijgggl.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gt2kuhvieqe.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gt2riygmnur.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gt2zmnjohic.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gt2vluvxxzb.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gt2kiqifnax.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gt2algakzkm.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2tmaugcdu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2yyafelyy.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gt2hxehvqvp.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gt2pftvqqwa.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gt2tiyotcfv.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2mkhzahux.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gt2eejbvecy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gt2oddjvtax.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2aebnpoaj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqpyobxe.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gt2lyigvokg.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2selorajq.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2uqefpxut.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2nsdbcqbo.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2uapxczmr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypqpqanl.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2rtvlcwjl.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gt2uddzkmak.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gt2zhdswrdc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gt2ealeemqe.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2iogwuylt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2siqhbugl.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2reynjpkb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gt2sakxoxiu.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gt2sddfwrxc.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvumlwnz.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2cvzksjsf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gt2irodlyfe.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gt2npjptkxa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gt2qvcyowcr.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2fbpawawq.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2doaoxbse.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2urszrdvu.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gt2irnrqjcz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2thcmvqsm.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2zcqrrbcz.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2fsuzblgb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqxgzmxr.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2pmcwyoen.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2irvkldyt.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gt2ifftxuip.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfpjpecj.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gt2eezpttut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gt2gpoylshk.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2mfpvmmeb.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gt2mfwkstta.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drmtswao.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gt2elehjmzb.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gt2tbwinvhk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gt2xsggyecy.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2gidradmt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gt2nbtrfbwk.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gt2afqvqyfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2tweltevb.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gt2vwylbfwg.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2skheachu.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2zfmmbqqg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gt2hrhmcymo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gt2dqcajmxz.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2yolepvxj.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gt2yuyyzzoe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2xdpdmxov.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2gtxoxylw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gt2pemigjqx.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjjvioyv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gt2mwqglltr.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2vygltjkn.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gt2kwqytuwx.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gt2ngdxfbxl.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gt2vzyvbwdw.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2esqxkhkt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gt2yzegeqxs.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2opmcyghe.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gt2euxavfwf.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neosdfsh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbbvjnjg.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2opasozhn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2txjbjpza.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkcplmrn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gt2wnurwilt.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2hfaqijms.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjikfbdr.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2mlrrwsoy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2axybogvw.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2thowbyow.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2doadilia.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2gqqghucd.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghdrxsrq.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2ubtxsrez.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2ktvdxzlx.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gt2tzqbfeyh.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gt2zrvhzwps.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gt2eiyzdeql.html


<!-- 参考信息 -->