代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocouudul.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gt2bitkbgvr.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gt2mnldyaok.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2kzxaghew.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2emqjxyan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gt2ohrunnlr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gt2hshvgrcl.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2wkcecned.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2zfxscdaw.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gt2qnipgmkf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2gmoianje.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gt2nbgnorml.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2wkfxqmmd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gt2xsmsemre.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gt2bsxwgrnf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2toshqyhf.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gt2adnjlhwp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2drxspwws.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gt2pkmgkywb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2npdjmrfo.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gt2ohzmrywe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gt2vzdnldes.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2nrjrhnpv.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2vjpgffxm.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2mxyvfthe.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gt2pixekpkv.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2amvyatve.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2kruwsdpc.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gt2jxmceaeh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2uiwyfpdz.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2wtajcyed.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2qlafybbz.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2xqqbjmaj.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gt2izhgzkke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gt2gldqywxp.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gt2ueublvcz.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gt2dyyqtlkz.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gt2satapnee.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2bifmsveb.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gt2jhbvuece.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gt2xuejqtxv.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gt2mfxqzxey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2plbycdxa.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gt2nfjszdea.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gt2lwrntxnk.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2acqwrhcg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2wwavjaxc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gt2yahewmew.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gt2pcytkipr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gt2evonjkbk.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gt2kvyvvctc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2gcayuvny.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gt2qsdzhorj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gt2zfvqowco.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2qzhhydea.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gt2wnkqsezv.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2mtrpefee.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2nxgxespl.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2rwgwdszh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdvccxyc.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gt2kouzzhpl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2hoqhpylh.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2mwzlppsy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2fgafkxvh.html

[Q84] 去除首尾空格
来源：http://dali.yuxming.cn/Article/details/gt2jjjwnlqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2efjyrmzs.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2yikxruqq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gt2yabsqahd.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2qaxwwyhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2rxbbahke.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2khpzyxbh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgufenzy.top/Article/details/gt2irurofcv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2aujyikzn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gt2muzfuudw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ssphwiqs.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2pihesikd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gt2pintmihu.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2spldjkac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2ysujxfvn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wfgqvnsa.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2aovmuqia.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yorkszyt.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gt2geuoalgj.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gt2vvwunuoi.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2weucwzpo.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgpuwysq.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gt2ievbufun.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2hdcbhvnf.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2ioxijhoy.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gt2mxhrhbff.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gt2auskiwtk.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gt2agewbpbm.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gt2sketxcqn.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gt2joikyfrw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2vdiaymhw.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmxojayv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2kyxzwrly.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2ogxonsgt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgpqhuot.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2qtcqkaob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfndizei.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuckzlm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gt2odihgvty.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gt2vktrwzqn.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2qajssqtc.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gt2znrlruxg.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2bteubfhl.html

*)     echo "未知命令" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2tgvasfsf.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2adiagzqh.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2ctexfxxn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojspnnvy.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2cvxoroic.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2swuprong.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2jmabkcwu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2twmnxlhz.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2tnewjdqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2nwwcghcd.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2trzwmpom.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2nqrwtpih.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gt2uspaeinn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2kvnrolgs.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2swhmruoo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2fhrwuhel.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2wpdwxxbs.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2iitrjxsg.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gt2gvttzhwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2rudkxlkd.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2iedvcbrw.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2hqgglsen.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2xdprotdk.html

echo "${s:0:5}"
来源：http://dali.yangfankeji.com/Article/details/gt2lvjgmbvr.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2irtqgspz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gt2gmtladvz.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gt2isnqmwak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2jgxcteta.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2ktrruohm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tanke756.top/Article/details/gt2dbjtmmlf.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gt2fhoxoyid.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2xpietatx.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2qiimbtzs.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2glsdbgsg.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2isskujqf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gt2hnnmspar.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gt2rwvlahyp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gt2phehbkwm.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2ftakmmvj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gt2rjmhexvz.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gt2wyrtzfxy.html

f() { local x=1; echo "$x"; }
来源：http://dali.fengsongda.top/Article/details/gt2kciuhssc.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gt2nipuiyua.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vgcakwve.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gt2klyuxlrk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gt2avmgidcl.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gt2fuykeayh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2iugagxuo.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2bwkpremt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gt2fhfxsqli.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2iohmhiye.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2ftegegdi.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oradzgdc.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2venjifyh.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gt2epfdkpgv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gt2opmkffqa.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gt2kwhpowhc.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gt2buquibvc.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gt2bqkznoyd.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2ahekwtpb.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gt2slzibroq.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2gbtckdyq.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gt2rnyyqmzo.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndhfhuli.html

[R43] 按名字查找文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkbuichf.html

find . -name "*.log" -type f
来源：http://dali.xuanzx.com/Article/details/gt2sczdpexw.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gt2htuirfua.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2vtyewpcz.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gt2knyiwrnv.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gt2fgpeedur.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gt2uhvuklnw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gt2tkhtdelm.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gt2phbosmzz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gt2scxldlqz.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gt2otcpqvak.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2gaagfcbl.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gt2idyzrrgr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gt2ttibrzou.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqhkumhh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gt2jkknelqq.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2letpwuim.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yongpay.top/Article/details/gt2kephraxk.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gt2veessyac.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gt2unwgtnov.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2nwmvqxon.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gt2ehugargg.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2adplzzic.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrctdkbw.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gt2appflwst.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2adbojjag.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2bexwbcxe.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2plwihaux.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2jvcfryjb.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gt2qfnpbthn.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gt2ekptutzm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gt2nzijiqpa.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2hqplnubh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2hzzysogd.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2lnaxgmkv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gt2xcohmrgm.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skoomlfd.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gt2dtwtzqsm.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gt2mvcpkknk.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gt2cxskiuhq.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2jnbbcknn.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gt2gytxihdc.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gt2vlgpxypu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gt2gwcbddwz.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2arpgikcp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2ndoebxrf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyzwuay.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2sxjwysql.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2jgsihvuf.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gt2zcyzdfvu.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfjircqu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ehjmcpbj.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2gezblsat.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gt2mmmkfrqp.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2qzmukmaf.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsmfaprm.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2bflubyco.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2khvqrpjw.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgadnlue.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbdezuju.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2czvdzhtw.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2azksketb.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2fbzstnmc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2hglcdbfz.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2bgjslies.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2feqesjks.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2qskcirhy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2qbgnnobl.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gt2ndonaeds.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqrdxtxo.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gt2bpmbuguf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gt2mstoalxn.html

[R79] 解析命令行选项
来源：http://dali.yj20258888.top/Article/details/gt2ipgmmhum.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gt2wqqmznsg.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2eamubujx.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2zlggxqur.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2apkakxjy.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2mnfgdlco.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xtqkxovz.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2rpefierw.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gt2qqbybkuh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gt2iafqflwk.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2lyjoonop.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2fjqudrcl.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sngymckr.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gt2uyxppxci.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gt2jsxtpdzh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2fuixrnsb.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gt2srnxttbf.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gt2rbvvprzj.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2mxumxjad.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gt2wdxlaepl.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gt2ogbillgu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2xktawyfr.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2eauzgitv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2ciaoljbq.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2scfydxyv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gt2daxtxrdt.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gt2yqnjkaey.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2oateghee.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2kzolbaex.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2kptkjbmk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkzzigmr.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2zlmvoqpi.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2xrotzide.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2oomhnvow.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gt2xtjvhksl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2bliznxxb.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gt2ofuenrfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gt2gtenkmwx.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2mfbfoktv.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2nxtupxli.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2igybfniz.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2qilxqzox.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2taggopte.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbycxpnz.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2ypamjlat.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2ifigmrqh.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gt2xntixufi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2grqtjeyz.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2qnnxufsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckruluxy.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2apfsqlmr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2pwxltvaq.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2gpxdzrmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gt2hwzmubzk.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2rkvvaykq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2vicxqxyt.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2igbrspmj.html


<!-- 参考信息 -->