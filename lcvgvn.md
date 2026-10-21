代发 wailian999

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtcieattiv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtbytfwhjs.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gtstnaxbwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtmfljemwj.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gtrrqnonlu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtaqaoysaz.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gtfjishmnv.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtkeerpuzx.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtxdbczfti.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gthafcaeuh.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjnclkdf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtzrjysrcs.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtbqfzzcsz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtoalrexoc.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruonmlxw.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtuxzphfvh.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtfdjwxzqp.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtupbgvydp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiwerhew.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtanslcurr.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtuzdhjhda.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gttnybsliv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtdqmhznqc.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtfdpisoiq.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtxpxghcig.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtynqdvtdq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtryinlkww.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtbmmxtprf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtrqnzuqcs.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtvfhqiocv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtjrafhywo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtvwtnefaj.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtdvurzaqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtuomcpdyq.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtnqyzxztj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtwghiykbm.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtdxghghiy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtfxxafrrt.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtadutxnyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtdhbqgeog.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtyqynbyyo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtpsilidli.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtpteqmorz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmoghwccw.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtlgnccryn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtuoblprqu.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtkmymhdyl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtircfghcq.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtlssgoysq.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtclmkwhnv.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtfydfovnt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtmuqeioil.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtrrqmeazu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtfyxbnetk.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtrvnsuyvj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtuicurorw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtxfmzkmzs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtlvpedhei.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpnrmculf.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtqlricjar.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtkehfibgo.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtjmhchqus.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtayxjplqd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbghiuepg.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtlmuvyhyj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gteucztram.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtexudbovc.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtrxjelhos.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtdrpzbwmb.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtloxtgiqt.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtwuvqbjzb.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtqprtgcxe.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtqvtlgfcn.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtpaliiktl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gtqevhwgfq.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtjotntszf.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtvotajbks.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtdrlxuivx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gtzruanuyr.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtdzyfstrm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtngguskpc.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtrdyqepxs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtdbxymhus.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtflkzpnnw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtstrmkqna.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gtrezzexnp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtpquuvjmr.html

[R11] case 多分支
来源：http://dali.mhx1999.top/Article/details/gtvvjvsblg.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtpgjgduvv.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtsosxejqs.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtcxwxuqxk.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtugfjyvyb.html

esac
来源：http://dali.xziqi.cn/Article/details/gtcgkrrsqt.html

[R12] for 遍历文件
来源：http://dali.jyoumei.cn/Article/details/gtgdejgchq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtivfusfud.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvvgtgcx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtzrhlguvg.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtstyfbfdh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtenjqvuir.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdfyjgiwa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtfyebdigk.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gtyzhmjvof.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehjwdmvi.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtvveekuip.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtxnqzpath.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtmrzgqrpf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtbxijapzu.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtdmqiojaa.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtzcreyobv.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtcbcvuyll.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtcrdpruzx.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gttfblfvbb.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtzqtzqckn.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtvyhclyif.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtzqypkhis.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtjzbdmmof.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtnsxuopfe.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtwznftmml.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxqdpiuez.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtmeknkdyc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtbhbuyhxt.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtiskbhyrk.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gthijaovap.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtyoovpcbh.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtmklzfiod.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtujubdzgv.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gtpsfyslhu.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtjytqcljx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtayrtpest.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtqlvdivkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtaqkugfji.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtcqayuxud.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtinzmtquy.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtdajaiiit.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gturjvxovp.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtbgkznrsa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtdjosfzmn.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gtclqbhonu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtchwaawld.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtttjtgsmo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.vqdsnc.cn/Article/details/gtzdcfhler.html

[R36] 并发执行多个任务
来源：http://dali.gzhubu.top/Article/details/gtdcxccaxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtpgqbzile.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtqjqjghqx.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtslrwmnhv.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtvgzontex.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtbljdlzdv.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gtaryttcdg.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gthedjsjuk.html

[R40] 追加写日志
来源：http://dali.jinqigfzy.top/Article/details/gtlktufiac.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtdzefrdxx.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gthrysqnhi.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtfpbgbkok.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gtiuafbmwm.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gticowhjlc.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtgbhuoaio.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtenxdckux.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtaoczckgf.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtqmjpuarn.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gttjumkqyw.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjraunn.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjijnktts.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtzkftcfsc.html

[R47] sed 单行替换
来源：http://dali.sweek.top/Article/details/gtxcatgpms.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtskoynjpk.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtzdfjbedd.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtxhbugfuw.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtyeefatgz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtpyircxzj.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtvhttrujy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtyyqzuoxq.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gteqobobph.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtaxkdrbfc.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtxwzkhdzb.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtzlyuzmlt.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtcmebeqkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtyxayndrd.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtbdkssltg.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtexelwmko.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtlhxwhwgc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtqfxphjip.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gtqlpoieix.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtmeyisaie.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gtvrjoxmct.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtfhsugbge.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtxjhezhjx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtxvlooubj.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtkmdggpwx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtuplreofw.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtejcjdkfy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtqoqqfiwa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtjyofoqhk.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtleyrfguj.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtamdrdubu.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtjsaejpyh.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gthfqysiai.html

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtvwgljwud.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gttcjhlcnf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxinkj.top/Article/details/gtbhekshwz.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtxqboynmm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfjsxfws.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtjilvqril.html

crontab -e;  crontab -l
来源：http://dali.ppjwa.cn/Article/details/gtuglecxpi.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gthmubnpnq.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtkzkigxoq.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtfxokxbqm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gotoacloud.top/Article/details/gtkwuvaelm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtzstdbeqk.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gththabmwv.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtmwtokwlg.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gtjfdqrjia.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtlkjajhbe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtauswxolk.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtfxbofeen.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtuoldoecj.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gtgmcknsky.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtnnaiklnr.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtiajlntrv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtiejrxeub.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtgkjtwxiv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtpzrmmwat.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtloplpgap.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtakcfpxhy.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtigsvhkqw.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gtdqsatqpy.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtwkzbcmox.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtlhvwkvyh.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gthccyauoz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gttgxxwczd.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gtuilxuufg.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtxvrajcfi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gterqbksog.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtfrilngwm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthasbxwxq.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtmbhpuvmj.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtqywznvwh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtemlkomws.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gteqryjcnu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gthgofuovr.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtxuycdbhr.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtxozelher.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtnhzxqqzv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gtnvsjqgmd.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtnltfjodp.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtfcpkpjwv.html

[S06] C：字符串比较
来源：http://dali.jyoumei.cn/Article/details/gthmnboadb.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtjpaljurh.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtjjyrrdgu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtamwbtleu.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gtaorzjxha.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtebhtcvzz.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtyjbeqhob.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtnxbznjax.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtnndvduqd.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddqsctxh.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtwwlxwszl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gthjoynzvh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtjzpqwoun.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtuuagtxfv.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gthwyztgox.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtcjokjdks.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtzklakdwe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtmvaowvns.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtbxypqjac.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtssziyliq.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtjnxdfunl.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtcrpmqcmp.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcxutyst.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gttjfdrhsq.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtxpixaazp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtbfzrwout.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtofnastzz.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtcqfubotr.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gttirzlkez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtrowtvgph.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtipilqdtv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtftmqpfrb.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gteorxnpma.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtthgkzsuk.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtizswsipm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtzdwkesdl.html

[S23] C：随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsfvihlq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtmmorzddb.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtrnhiswso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtwjywffls.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtesqcsear.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtkzgftqpo.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtoudbnmwr.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtewmwkebn.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gttipxrgof.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtplhyklbe.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtkfureorl.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtjuiuticv.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtbcvbwjgo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtwzbbnrve.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtdbzslyge.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtvkbflpld.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtceijypnc.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtwikkrhso.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtjxnygitu.html


<!-- 参考信息 -->