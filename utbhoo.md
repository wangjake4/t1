代发 wailian999

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtedulnadp.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtazzbjjwo.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtltcskchu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtluyqsquu.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtjvxpcjga.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gttsiflwjd.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtvnkwfzht.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtuvxkslkg.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtntvquyda.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gtyfbakrvd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtwuecqwgl.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gthneguxsv.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtyunaoicn.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtkmegzlma.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtwhgkwnbq.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtwpmvhjie.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtifudvnlp.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtdlfevpnt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gtdkqwwemi.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtkhhgtsnp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtietojtxu.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtfmrgklce.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtqnokldmj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtxtaxijkf.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtlsknnmti.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtdslnidkn.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtsolirybq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtqionzhmg.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtvkklaagc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtehjwoeni.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gthbdctuiu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtjvqmlcjn.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtjwjqnwad.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsanqzzwd.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtdpwnamuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtryajxbrh.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtvqqxweup.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfnwxhbze.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtmmtvrqdr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtfoqvekxx.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gtslvdhbmh.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtiynqrgiq.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtjfevkgpq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gtomgegbyu.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtdgoxhbgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gttkcspeff.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gthpbfyybp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gtyqkbxxgy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtsqaefqvx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtzfqagfjp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gtqajosiwi.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtoggzcejz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtjqkmgtiv.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtvwqyjpcu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtchjurvfj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrhabczu.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtqegbfopv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtaszgbvgq.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtvlklnsml.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gttffunodh.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtdnhfpkxn.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtiiycquym.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtoyurnijf.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtddzzotlf.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtsxufdjot.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtugvefgqj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtztkkaelf.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtgkscdujy.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodfivwva.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtipsqohyj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtkdrrglir.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdatjowlh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gteejltglh.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtollkjuds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtcvxnimiw.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtuqqdheaj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gticojcpxe.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtsbxazmdp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtyhznhhey.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtphadrlxm.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyfkzdoz.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtyphphouz.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtahdmfpim.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtddeizfgr.html

esac
来源：http://dali.ydzc1.top/Article/details/gtnyoeyogq.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtsmvdodhl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtjmnjchgl.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtsfkohkku.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtrommubss.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtxjgndkaz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtrufkwgda.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtmwhvbcwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtvdkcflut.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtwsqgxlve.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtujaokgkz.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gttpzopkpc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtoxtbzrzq.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtczdvlkaq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gteheazfzj.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtxswdjltj.html

echo "${#arr[@]}"
来源：http://dali.nanxinkj.top/Article/details/gtocgiesqf.html

[R20] 关联数组（字典）
来源：http://dali.chenzaomai.com/Article/details/gtzqhfuozd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtxkmjkfcz.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtakvwbcur.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtfzaexviq.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtkplyfpsy.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtzvdhbktf.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtebztaoiq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtocpeudwk.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsokuvfu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtttsjluah.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtgvauyycn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtpjnwbuse.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gtidewnuhg.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gtdrddurmj.html

[R27] 算术展开
来源：http://dali.zhongyouzk.top/Article/details/gtmslttfhw.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtgqbkefzh.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtdtuimomz.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gttzaxerwz.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtwcoqlach.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtgyvdwcho.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gtzqicvmrj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtreiwfqjn.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gtgcwaojph.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gtqipqrbuy.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtveesceoz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpxijoeex.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtdnqdkgzj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtaeirlzki.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtvuhsurqg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtgysfxkcd.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtazftxcoi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gtvyihmzib.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqpeclnj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtsflcflwu.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtekjkebjz.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtqkudvmal.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtvsagxhzf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gteboniabw.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtkwpqaluk.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtveqncilg.html

[R40] 追加写日志
来源：http://dali.jyoumei.cn/Article/details/gtvniwzrjk.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtxcfsnmll.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtfnqajwyr.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzyrhayi.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtjhbsrweu.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtbkikmump.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtgwjuprad.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbmpqedn.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtgsbulymk.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtugiixrdz.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gtgtctqcyp.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtrtmrzsln.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtksmcighi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtzkqqgrqk.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtzpybaslj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtqpjonbuo.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtktfbibnl.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtederykdf.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtzvanqjcr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtlwwcphpo.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtxnvgpvlu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtruuvaugh.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtwikzlzbo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtrwuiecdy.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtbvkxlchy.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtefhkwbkb.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtdyymitrf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtnffwxfms.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gtnhcnuqbp.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gtbvyqkbdf.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gttntvsuah.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtxkutiyvi.html

[R56] 远程拷贝
来源：http://dali.iojbl.cn/Article/details/gtznbsmucw.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gttjcibpwq.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gttzfklthy.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtpcvqucnp.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtchvxhzbo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.meibo888.top/Article/details/gtkyypqszo.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtfchbqhyq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaxydsct.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtjrkmddfd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtrbcjjinu.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtmralmppe.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gtunstxnro.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtswtlikzp.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gthsirjxkx.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtleqyjzgw.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtsekcrsgm.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafwebkwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gthuvlcbrp.html

[R65] 查看端口占用
来源：http://dali.jyoumei.cn/Article/details/gtmpmegpci.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyawdvhnw.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtfwhxhcuz.html

crontab -e;  crontab -l
来源：http://dali.zdqjudy.top/Article/details/gtpdrrrxqv.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gttnbgxsix.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtxcuejrlv.html

[R68] 计算文件校验值
来源：http://dali.yongpay.top/Article/details/gtfgyzzewr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.smart0.xyz/Article/details/gtttkjxkhz.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gttpgmskud.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtmilcdttr.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtbeosckne.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtftvppdyu.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtydxtypqv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbgjphrx.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtpvmtblnk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtuzmpepwb.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtaroahanr.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtpohthngd.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtikkxhllt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtemkcexfo.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtnpqzqwbs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtmcfyiczv.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtgtwpvuyc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtiagimyvr.html

[R77] 读取用户输入
来源：http://dali.guannengcc.top/Article/details/gtgrawpalb.html

read -rp "请输入: " ans
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaaujycz.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtqebrlwlf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtrblzjlrn.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtbmhqbqlr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtfptppqoq.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtleoputcx.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtghegfzha.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkfkrfibe.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtmqahpong.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjdzkljev.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtdxwgvooo.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtwycoytyc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtnejvzjbu.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtntwbqgfn.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gthpwhtkao.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtexcltwdc.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtrjafwphw.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gtykottadw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtzrobbqbx.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtfeaufwso.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtbqkowqzt.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtglvteziv.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtvcadpuvm.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gtrbluilxn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtcxxfrhvl.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtkkerficz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtwlnrhfrz.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtfvgnjbkj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gtcsyrtrgg.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gttdyyrjsq.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtrgwdsjuk.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtqeykzsrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtvhxaoyrh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtlidnhfai.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtyucurvhh.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtkcaalrjj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gttqehrdnf.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtjdmfonfy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtkgnigbzb.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwetswaew.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtcouysxkg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtiedyvzlt.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtwspzdtrt.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtmbaikufm.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtouhzewwf.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtlrnwlxco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtxbrrmmkc.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtddfkdsux.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtjcmcqaco.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtvkpcfkoa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtxnrojhzz.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtgxrxpnmg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbkrztga.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtkmbawoyt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtvxznrlcs.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtiveabakg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtstvzsdgh.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtfrfyjxdv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gttjaxmgcy.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtbhvetgjg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtphrumpzz.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtcxspjief.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtjzptuass.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtyovcyqfb.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtxfxcmmkt.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtknhuqaub.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtzmcfmmgn.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gttwdflypu.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtywexrble.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtkdnxgvja.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtrvydblva.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gtlsnswbkq.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtzkuqwjbc.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtaeeoymtb.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gttuixdusk.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtveotdjpl.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihghkhhc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtyjpqwwng.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtywfgaifj.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtymttcgdd.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtffdrnmco.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtomjgilvq.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtnihtstzj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtjshlfswi.html


<!-- 参考信息 -->