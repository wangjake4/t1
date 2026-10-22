代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtdzeluunb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtoxrzmucw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtnbexvvvk.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtljchjjtr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtweejdoij.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gtvfnoiekk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtsnuxlncw.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtcogidyya.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtuoqvmuqu.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtbgogfjsl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtlxmicsyb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtfquusrtc.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtljzgugqt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtvawuvbyg.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtbvwviely.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtiuhfqrnh.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gtxhstjgbt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkamwwdr.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtxehukxbz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtvxfoaeob.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gtfmzccyfd.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtxelwkrsd.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtoyhzxlrm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtuhdxcugc.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkogorwln.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtlkrqxhur.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtvxefzxvr.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtqjeycyvt.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtprvfsrhw.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtcrzmciuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gtmtnmqcnl.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtlaoypxex.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtddxiilvh.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtvfjuisgx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtwtlsisau.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtffzsdaan.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtsjkppwis.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbudpzvi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtgupzrklt.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtwzquhvhe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtzrsariod.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtnedfrkhd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtuoorpfoi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtjalmewsq.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtluuktlef.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtsckytjez.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtkcblcwjz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtbfebxfky.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtdjgdjovp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gttypawzio.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtosudfxgf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gthdkqfhfn.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtgbdbddbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtreaglnzt.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtufvbwmnq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwvdaqzlp.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtxxdkehjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtnnortufg.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtqphixzue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtaiqovcoy.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtgvqmyise.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtxezbsnhj.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtsdmaylxg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtpjqmwjay.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtjulrbzsq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtpsilndct.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtozmkjmbb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbjcgihu.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpundhba.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtfhnaquwb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtoeootrgu.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtemtrftev.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqzxdpxc.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtxkywqmod.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtxhiiqotc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqadkmcmh.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtdaumdyah.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlrmxowvs.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtssarvfox.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtnthzmmao.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtpmgiznjc.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtwlugvald.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtgkxsicdl.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtwsozqokw.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtawlgeooo.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmipidnxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ppjwa.cn/Article/details/gtygzushhg.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtxozxwtye.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gtdfpscouq.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gterxvqbvi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtxbuzgzat.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtqbunxepc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtrvjoubjz.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtehnerghg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtpogkwjmd.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwzfgrdv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtmeqlezee.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtzzuikizg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzuzvlvg.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtuapsckkq.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtfbyvneqm.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtmobfaram.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpwagmfg.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtqyggpkqi.html

esac
来源：http://dali.hnqzz.top/Article/details/gtkkklteyx.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtuzcltygs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtiglfgibo.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtbiwypuyv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gttzgmjvcj.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtboljfezg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtfhwirbnc.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtohddchex.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtjmdyrrxz.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtkmhmfgjt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtwneppbce.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gteylntjzc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtyngklzqb.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtcgtqsnhh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtnsgceqdp.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtdwsbegtz.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtwvpafudk.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtlavwmwok.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gtulswimcj.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gthvqcafiq.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtsscfvoei.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtkkkgbpfs.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtshfwjbfe.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtrvjfzzpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gthixrngbk.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtevcnixua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtssbfonyk.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gtnoogoedi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtjrwuhakr.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gtvjdhragm.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gttxxqnmlw.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtialsfsjk.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtekehxmvc.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gttznuejgl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtgbmhyujc.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtkwaviqnv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pengpengdd.cyou/Article/details/gttnwuuiin.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtqhtjgduh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guannengcc.top/Article/details/gtyufsbsjy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtiostyuin.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtdqwupjyr.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gthsvmxobk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtltekhsmf.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtnpbjrfxo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gthdfdpmgx.html

[R34] 退出时清理
来源：http://dali.snrcjt.cn/Article/details/gtpcnbiudu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtcgwzvtyu.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtqbsbflmt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtcusjrimk.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gthhuqsovu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gteudbaayc.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcincmpin.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gteyfmhxmc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtkghzcpoh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtclkammaz.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtinafxdko.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmrjmjsl.html

[R40] 追加写日志
来源：http://dali.snrcjt.cn/Article/details/gtwazwqpwd.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtqujmlijw.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gtxxeqbctk.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtesrkvcdp.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gtmnqsxpcm.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtncacyybw.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gthlphkfmp.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtcwpmsjzp.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtngjazggb.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtndfpnhoy.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtaqdzfuxv.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtntxcluqk.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtceevnadc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtmcjnsaxh.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtvaitkqmb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gtkhmroaeh.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtvuikuvtb.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtmvaflxud.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtromowvxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzsdxwee.html

[R50] awk 求和
来源：http://dali.xinyue.icu/Article/details/gtiuygigcx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgkmjuos.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtuxfajhqg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtavyciqxo.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtbcagpbkc.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gtmrbxitjg.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtbnnckdct.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtcbtfjdwv.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvlcrqbj.html

diff a.txt b.txt
来源：http://dali.yonumen.top/Article/details/gtgvdutvwh.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtwwdoiyyp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtfteqxdqe.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtwamaxfru.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtrvnrdrzx.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtnkwwsckj.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtjqpktkln.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtpzpyuhvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gtltkuuvhh.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gtzinuflid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtcxwrjfwk.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gteziozlfc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtrkyqqoes.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gthzszlfoz.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gteanfwjqz.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtcbkcuwgt.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtobjnwoww.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgcnocob.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtazglxzrk.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtredfyngc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtxijzagcy.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtvlqhagdn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyearvvo.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtesblqhyw.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtgkmctxao.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtvgixjvch.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtayxcdvek.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtyrkgrgap.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtyfrmfcpr.html

[R69] 生成随机密码
来源：http://dali.hongshengwenyu.top/Article/details/gtbofriffp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtykhgpzxi.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtatgapigg.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtzyyavnii.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtoxgkciyt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shzxlz.cn/Article/details/gteheyqfje.html

[R72] 等待端口就绪
来源：http://dali.hnqzz.top/Article/details/gtpdepdwsk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtbfmxqosz.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtdruwiknw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtdtuntcsm.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtuqyoveqr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gaohongyu789.top/Article/details/gtwyhiuczj.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtkjbsxuhl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtezpdslcg.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtnvhfsplp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtzptymbch.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtgpheyyyi.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtbulvgcmp.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtsznnpmnd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gtotixoxst.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtirlxloqi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.mhx1999.top/Article/details/gthlvskamg.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtpkgtigsu.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtaabinzsy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlqhuquwx.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtbpwahgjz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmlfkosxm.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtnvdxwbjr.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gthsgoyaxw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtmeufyrhq.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtqyralbdr.html

int a = 10; printf("%d\n", a);
来源：http://dali.birdmap.top/Article/details/gtcgqfvqnv.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtvhmkcouz.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtwmlvvxae.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtdvhrxobz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtypbdzjnu.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtgukvcpdu.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gtkkmwyhku.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtklfqqcdn.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtwsnrkqxy.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtnkyqegmq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtjwkaigvu.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwguleyu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtfzhngwoq.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtposgaaol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gtrigmthdt.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtczoenvpz.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtbympktgu.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztbwknnd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtfwtmlqsu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtyixlmedi.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwxcnsug.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtassjdvol.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtatqcyprz.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtowzrjtlk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnetzqrgi.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gtbzwsaiqb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.9152youxi.cn/Article/details/gtgnfxytrw.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtezuftoez.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gtlwcqizaf.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtkyfulaib.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtdjytvlwn.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtffdmjqtv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtuxrvijzk.html

[S18] C：命令行参数
来源：http://dali.fengsongda.top/Article/details/gtcyhukxlg.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtveonswkb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtwjnyzsav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gthwujxkzu.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gthqevmerk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtiwvlinof.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtkxtralsy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtdbrkuqjr.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtfggmkckt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtpigunweq.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtwwgjtikk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyfwesdm.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtpyxhgjvl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtbpxkqabj.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtjeimlmbq.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtiegrgtoy.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtkbfqumpw.html


<!-- 参考信息 -->