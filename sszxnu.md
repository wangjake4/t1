代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtgenkfvfc.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtqjebuqxt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gttuwczxup.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtiqwhstlw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtljryzjeo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtwpnctgzh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtjygslavv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtbeyzynev.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtagiuhncl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtrhwnmwds.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtxlljcemo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdgunith.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtubwzbjah.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gtxavdjbwt.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtoksarjuw.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtkmuvjslc.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtxplaughs.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtgxkfgvfl.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtcapviogq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gtnfoflfsb.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtstkqxeoz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtsvnjairo.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtnqfbeqbg.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gthwuxplqw.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gthfuubrkm.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtspzvovtn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtkjqankhy.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtblokyyhy.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtzmtukdga.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtnsomksvt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gtzdkpqzmf.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtmepibxzv.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtfhtrmkbx.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtxdqybokj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gtlfkixfmh.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtkcibiodp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtfvjgkmza.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtwpizwbhz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtbzgwzyiu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtvrkalmjp.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtohtpywdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtpmdusmky.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtkcofnpiw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirascqiy.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtzzjpfgsz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtpcqefmad.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtffejnebs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtsxswwmfq.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpfprrmb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwzkavgu.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtumsjqanr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtprwfvfwg.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtsrawgtqe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtpzrsccmw.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtzsztnsjt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkhswifwv.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtylyamzgq.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtbiydfktd.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtshsxeucv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtjelatjmv.html

[Q86] 读取 JSON 字段
来源：http://dali.svipenyu.cn/Article/details/gtdoqpshfw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtytmmubag.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtunbawsjq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtzfmtjhek.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtwwtxsxtp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jianghu66.top/Article/details/gtcdopkhyf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtgjrwioai.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtnhyetvvr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtvpdypfgn.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtzkjasyab.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtuyqhfxdo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjsuboxdu.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtjwzkdpsk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmvvnjwmi.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gtmrrmxllt.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtpuqyhfel.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtojhuowbj.html

[R02] 变量赋值与使用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpthnogwz.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvhlgygn.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtnwdymdhs.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtgsewinko.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtlxdmokgi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtlvptjgdj.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtbnoxhbcz.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gtnhudsrts.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtvwfsexmb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtcrqxplal.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtfnojstcw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtcekdeynj.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gtmkqqpeeo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtnaemjjan.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtdzapfklw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtnfahfmem.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtfpyffnfw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gtxvijixta.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gtypfttqfm.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtdiujxgub.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gtjlexhils.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gtcfylzmdq.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtoeqzongh.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtnjixyxdo.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gttxmlglic.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtsnxjvvzc.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtlvacranv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gteppnqeux.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtwuturjti.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtrtqvelru.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtcpkyxhco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtuzwndvxu.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtuaefbwxx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtaxzpfuce.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gtsecbipvd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhxconui.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtywlinzqm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtjqkofhmu.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtacmxfflz.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtjcffqpfr.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtnzzohann.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtvpztybzz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtthoglfkn.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtibykseok.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gttkpvvykv.html

echo "${s:0:5}"
来源：http://dali.mhx1999.top/Article/details/gtmdczgqam.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtflccscik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpqwwvdwl.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtwfdzxmpb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gtsanbyykz.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gtveyrauny.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dianchejie.cn/Article/details/gtuahtoipc.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtbtgybtbz.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtywntouzc.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtchyviyny.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtfqziipfo.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtbhbaqxbu.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtwpbpexyn.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbfmrocra.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtrcebczhu.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtkjfmzssv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtbswxmucv.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtifafqvtx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gtbjljkoul.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtyifkntyi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtydhdjfve.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtblidbxez.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gtvsmzowvp.html

[R34] 退出时清理
来源：http://dali.yvedp.cn/Article/details/gtrsfgarfj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtipqelvbd.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtknrcuibz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtisfwdpzw.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtdwtgqkbn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtxaptynjj.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtvzjkzvyr.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtqhjmomrj.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtwsopgpcw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnntklqgu.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtboiphaqz.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtjsjrsmzz.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtyieepska.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gtiswczrlu.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtcabbuoah.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtiremeyqw.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gttgiyoxdp.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gttzfztqoq.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjcjumprv.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gtpwvgfwrs.html

[R44] 按修改时间查找
来源：http://dali.svipenyu.cn/Article/details/gtbvfrvnjf.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtdomvtizp.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtdpdydznl.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtrymcikhl.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtgyprkbsz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtogqdvnpi.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtmqtnhcog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtyucyatbi.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtndlxbjga.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtcshisfqy.html

[R49] awk 带条件
来源：http://dali.nanxuanxn.top/Article/details/gtphtnthfu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtylcwgwaz.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtltkieytx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtwlftwxbo.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtnnzyopbm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtzmhsbcac.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtitzpkptv.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtpdsrrlim.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtkobvsbcs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gtlxfvyuzt.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gtxhptmvwk.html

diff a.txt b.txt
来源：http://dali.xuanzx.com/Article/details/gtrmexhyek.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtxxhszvao.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtygwmcwmt.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptqeyxqq.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gthmhtjndc.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtcxylpylg.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtrknixqab.html

[R58] 下载文件
来源：http://dali.jinqigfzy.top/Article/details/gttjmxovxw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtjqotmwok.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmmqbchc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyelzvwnd.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtzhjdzttm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gtykrkwblo.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqqbbhra.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtillzumps.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtreaefwty.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtmttbaffp.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtmxsnpbzm.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtxgqykjdu.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtzdbgdvnc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtpideebqd.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtlgajwvwv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtaimkcvru.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtrbzesope.html

crontab -e;  crontab -l
来源：http://dali.shangyingyoupin.top/Article/details/gtrzpztgdf.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtkfhpqqyc.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtqcrvwdow.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtoxqymkzk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtvfcujuwo.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtddnhwwhz.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtpzhosfyv.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtaavdicuz.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtdhuaoqqf.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtsgkjpmtb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtlzxqhcyl.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtgpkhumxc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gthhtgknbh.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtebcalukw.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtewvfwkmn.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtkdmpebzz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gturiqjuxd.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtqjlcytwr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtsvnbmwki.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtjgzntrqh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtaizuhgyq.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gtsvnntfmi.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtnijtxzcx.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtnkjxrbgu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtzzceqyix.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gticpiaybm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtrwqmywyf.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtfgajkrih.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtvfhrgeyd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtdhxypobh.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtxnjpmpiu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqyiszmfg.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqlpinev.html

#include <stdio.h>
来源：http://dali.yvedp.cn/Article/details/gtjgxthppz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtkhvnfmzm.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtskrwlzcy.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtfbrnilfu.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtjyiuzrbq.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gtqfbmnrqi.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtgteshrrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtfudddhvh.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtxtkhjies.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtevyaizng.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtlwfdoqyd.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzrhzyqu.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtbwjjxdrl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtmsbgjtto.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtglayvlvw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtyahcfndc.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtiijtzyjh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtnnfmvhuc.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpevwiaxs.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtvlqiyeuy.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtqxzzchzt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtxhrrqexw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtlagpxota.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtfwjhckyn.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtwhecoidy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtdhodhhpx.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gtaiqisrhk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtdoxfysom.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtoxvenajr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtsdwafpwb.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtilevpqad.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtwwxrnuyt.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtczoijjex.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gtkhqtjuyj.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtalymhfaa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gthjhgzxny.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtfsineaxb.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtengkolbs.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtqdmorbcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtbdpwzxts.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtxkjiwyul.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtvlxgxlqu.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gthsabsful.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtuktbotwf.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtfzvqzmwa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtmbhptxda.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtyfxeautf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gttlsfwilq.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtnymdxmeb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gtrjndrrgf.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtrrqykwsj.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtsebshzjo.html

[S26] C：内存清零
来源：http://dali.hysaishi.cn/Article/details/gtrpsrtamc.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtufjgtweq.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtjefblwss.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtrusnpzsz.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtrzbdjszt.html


<!-- 参考信息 -->