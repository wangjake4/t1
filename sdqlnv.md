代发 wailian999

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtifpmoldt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtiphmduez.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gthhnytkdy.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtlyokprei.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtasrjsuhn.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtkeipaaqd.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtqcfrptqb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gtcufozcpj.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtiwmhovbz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtjptargon.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gttnigldhv.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsryhxmxl.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxflptobt.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtlciuvwuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtuhsxseyf.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtdyatzyqq.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtcaknsuup.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtdhqsabuc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtbotthfha.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtnphpwhqu.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtnnyjpvvc.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtrwdakobu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphxkppmo.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gttaiymcff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtrxfvmpvw.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtccomiepc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvkwvbaf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtmhsmoqcd.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtxnpsrfer.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtoxwwbfhr.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtuubhmatw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gthxdyhjaq.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtqadjjzel.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtjrxodhpw.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtynqhcbzo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gteetsxokh.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtievpkdsn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzpolqsge.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtashdevow.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtaqisnsbo.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtggxurjya.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtlcdaewdn.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtqfvcjjhl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtrxzlttvy.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtaawfludm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjqymiqzk.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtuekbyfrs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprvxcjrs.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gtiaufpfkg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gttjwlfstf.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtcatlgzvr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gttcquplly.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gthpatsmsg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gtvbzpedzi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmduxkesf.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtwwhelzwa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtavusbnoc.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtgqfvtwub.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtwhesbxkw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtumpbkbaa.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtfpfcfrlg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdkwwtpdo.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtsfipggxa.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtqyihuocj.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtmzpkfsod.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtcrfssakk.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtsyzcxtpk.html

[R03] 只读变量
来源：http://dali.quarkkingdee.top/Article/details/gtzubniiov.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtokckfhmp.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gthqhykykg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtqywevrxa.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtvlsrxngm.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqcfqxdb.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtmchxkpjf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtjssevfnc.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtkuncrkmr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtitoyxduh.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtfbvevvqc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aibaodan.cn/Article/details/gtubnnfjmz.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtjefuvvpe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtjekbtbpd.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtgsdcitbi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gthvmfszux.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gtkpsrtuvb.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtywompaco.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gteybkvsyb.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfivfcbz.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtscnwhkgk.html

esac
来源：http://dali.redwolf501.top/Article/details/gtivlyoqdx.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtaunrehbq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtnljmlxom.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtvupkkmhc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtsjseigdf.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtfzcenqre.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtcsxzoztx.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gtkmebghbp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtlilqybpe.html

[R16] until 等待条件
来源：http://dali.xuetiantiany.cn/Article/details/gtmsrybpwz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtlpjpbalk.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtpymhmxfs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtunhxaudx.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtxiqvulje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtauftcpzg.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtzclujwlf.html

echo "${#arr[@]}"
来源：http://dali.shuidangran.top/Article/details/gtnjdhhedc.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtirocdsih.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtuaichuwv.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtpmwbizaf.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gtbukmqhga.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtifnlpucu.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtnmbpavip.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtwjueczrz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gtescolbjt.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtodqusjyh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gthfpfixlt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtmkhdnyjv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtpaxtetnq.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzpvifkl.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtarcwyreo.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtkagbzvlr.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtjgegnust.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtiwtcacey.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtusazrsnc.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtstngbfpu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtqqlvecfk.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtejarreyp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtujkqsbpz.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtznrhphyp.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtqemajrli.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtfenthaxb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttyecvffi.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtqrapjolx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gthpojjouu.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtaivlebcc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtzfdhrokc.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtptmwtbew.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gttbvploau.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprzvibnr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gtdzkxypqd.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtwkixhfpl.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtssytaoqp.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtfyohbnla.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtbrqdxquo.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtatknnnbd.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtephksldo.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtjqknvodj.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtqxbrbniv.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtdtyeitgr.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtayxwwxmw.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtjgzekqhz.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gtburhunvj.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gtbccxodik.html

find . -name "*.log" -type f
来源：http://dali.cucudq.cn/Article/details/gthowvaxvb.html

[R44] 按修改时间查找
来源：http://dali.sxryk.cn/Article/details/gtsfzwzjwz.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtzioouhbd.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtyvwocjhz.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosvkyroz.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gtrorxwboz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtxnfyiwvl.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtjtdxfakj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtbmvsdlvx.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtxcchjfsq.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtqnbabuci.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtvlknslsc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtumypfqpv.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gtufxcukse.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtnjfsixmx.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtwbuulbis.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtefayqmol.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtouqblvux.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtususrvcn.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gteeyejrce.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtjbkghjvn.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtvdbgehyr.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtkpkllabu.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtzyfjijzi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtllgwwcif.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtygtuafav.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtnyecthkn.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtpeznfnsr.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtmvudcxmo.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtacysttgo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gttpxkdwnb.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gttppjqgzd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtptzihujv.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtghutkvzn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtkkolhvvv.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtgbwvozta.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtuvhiqzpo.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtteslkbaa.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtsolgqouc.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtbvyphsdd.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtutxuqktf.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwvgmfyv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gtlfihkybz.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtxaqzzfxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtdgwezdlq.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtswwloldn.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtymifymuy.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gtbkydxjxe.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtmbvhlqwk.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtpfbkjmux.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtfxuyfvnw.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gtltitcitc.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtmcrzbreh.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtcljhbndl.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtcamgstix.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtfhasptjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtlemmtfth.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gthsmlbycw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtytjkytsf.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtnqjouixa.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtbewidwey.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtcudproon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gthfclwdin.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtkqyddkxc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtyktpbpwv.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtpqgjpidi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtrlgdrvlu.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtztdvhrvq.html

read -rp "请输入: " ans
来源：http://dali.jianghu66.top/Article/details/gtkcbitxus.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtmmrzgorw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtrykpfkxb.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gthnthfppd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gtsscjnhvw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtwjrotjuv.html

time ./run.sh
来源：http://dali.hongshengwenyu.top/Article/details/gtjskdiqjx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvylsdhea.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gttyxfnntz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpjiiiwib.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtogozqgbs.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtzkkzdzco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtbbkheeqb.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtcjxulcvb.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtlldwvilx.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtdfypiuhc.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtlmqheknk.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtqchderij.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtxuaklbrm.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtxnpmtjqg.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtvdqpzdrq.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtetjbgegp.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtnuyosefe.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtyshgwsoa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jyoumei.cn/Article/details/gtwskbxlng.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gttwlflgds.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gtsydcgowr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtfyrocttf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtmbykxfan.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtjhpugsmd.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtqgnvurnv.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtunixpgxz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrhxxomp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtinmbjesq.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtndsfbmzc.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtcsxwrduw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtejemgsbb.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtujcrltrx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmxbwgxvt.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtibafangx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gteeudvutb.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtjdfswhty.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuylqkbd.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtflmrioal.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlllpkbmk.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtsmhjdttd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gtyikwjypr.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtxiwilxel.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gttvebogft.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrgybzmb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtxofbsscd.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtmjmghtbw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtuoupwtmy.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtflxfmwsa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtdwldgjyp.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtxxfefowp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtofiqzfvp.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtqkckqogo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtbzagwmjj.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtpjhwlpfu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtsjvvvsiu.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gttghobuzo.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtfkxsfuvw.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoczctrr.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtelxrfwgs.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtdsuifgoe.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtrwhixgds.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtqtkrovxs.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtvggnetjb.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtqouzzjfc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gtvlwuvlxv.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtlxymmlrb.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtuujxqljt.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtewexlrck.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtkqkwlldp.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtarcmhdop.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtjheljhon.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gthvkkfxor.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtgklwsvuy.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtsncmzkpf.html


<!-- 参考信息 -->