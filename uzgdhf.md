代发 wailian999

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2wktfpovi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2pxjpawxt.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2usgwfozk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2jwtadknq.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gt2bttnpdoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gt2jskfcsti.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gt2fguejfxv.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gt2vmofbcsz.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2afcxerxl.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2tvecrujw.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2uagsnrmx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gt2tlhvpvxy.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2jsbzefyj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2osvgrzar.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2lduzoxho.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2aooaooga.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2mqymvvdc.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2kihaysue.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2awmwnpfa.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gt2lpkdblqr.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gt2qtdvhwzb.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gt2lprdqnan.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2fencunwx.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2pzkahgtk.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nujjimbg.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zascogui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2trnlfmfz.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2xkipagts.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2vxotngbx.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2ldwkamcz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akhwdyfe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epawkzph.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdkverke.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gt2wrylymzc.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gt2ctmeuvjy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gt2ounrjozh.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gt2ugoktfup.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gt2fltcxblk.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2elxidilh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2vzkuuyhm.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2axdjylbf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2ocfebchy.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2dsonuqvu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2jfcbrrpj.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxdyojxp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2nvlrjwxb.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2ydkxqkvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2sapwhvba.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2dskhmvyb.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2pjleyddl.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gt2hqxccsdo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkurpxxz.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2docqkcys.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gt2usbxjone.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gt2hqdntysd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2abqivnkw.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gt2cegdwfqn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2rwywihyt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gt2myvwcznj.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2oabnchdm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2nelrualh.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gt2lsotodhl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2fvdubimx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jrltjido.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gt2brdfceei.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zydzpwjk.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2nuxajarh.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gt2gpahyfrz.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gt2ctnguher.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2aseifomy.html

name="Tom"; echo "$name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvdagmjl.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gt2gpfiugft.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gt2rahiflsx.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gt2lexqjleo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2kakohrvo.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gt2gnpiounr.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gt2pheiuphr.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2ygmofgwg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmbfnbwk.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gt2mvbxndqd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gt2hhogzgzm.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2iceynmih.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2gmpvgabi.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2iabanltu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2qbgjqize.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gt2pgdndoek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2vkjbojqo.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gt2yhawkdby.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2iyzrfdva.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wtvbnntn.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gt2uqchhevi.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2xqapnatk.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gt2eteixwae.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gt2aovyldtr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arnkdetv.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2swdkjape.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2iwghxmhv.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2zvbcygos.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2zheesbsv.html

[R15] while 逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2bgjziaie.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2gdniixye.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2yrektagy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2diwforqp.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viflzzfx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2rehmizal.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2bvwxvzxv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2dmgzvlkf.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2fpechdmv.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gt2ruqxhohy.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gt2gxxzevwh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipskwmaj.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2yxpuytpv.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gt2dnxjfqml.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2fcuevtbq.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcltotad.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2tzodnxlz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gt2amaozbpe.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2tssyhmdm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2utkviowj.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmlgldua.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2ffqunndp.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gt2jfxgmzzn.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2qjaodcbp.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gt2znvanvvn.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2kbfhydne.html

[R28] 浮点运算
来源：http://dali.xuanzx.com/Article/details/gt2mdpnsrvo.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gt2znpojpvq.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2arhqukwn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2gozyulso.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2eybuqlpf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2regrbxsx.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gt2qgaiaool.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gt2ldlmjkpq.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2ovirnysm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2qfthttea.html

[R33] 捕获错误并提示行号
来源：http://dali.dashuyun.cn/Article/details/gt2ssftcnrs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gt2jpvbeiue.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gt2orhuxxse.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2pjxkvjua.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gt2syhcqcqo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gt2hbdyrpxk.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyfduhhj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gt2gqutxlhh.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2jkvylakl.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bludktrn.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gt2jwzsywcw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sysykeji.top/Article/details/gt2saspvcps.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gt2eprocwlm.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2ielkhjrn.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhtiodls.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gt2xfuknaif.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2dkrwsyex.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2molawckz.html

[R42] 输入重定向
来源：http://dali.aibaodan.cn/Article/details/gt2qyjayxvt.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gt2esfyqzrc.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gt2lfgvfcnd.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2scbiwqxl.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2yvifdhfw.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gt2tlizrbwr.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2qdlyjhyu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuttayv.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2dlcwmyjo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gt2ueojrspg.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2exkemlgk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2igduylel.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gt2ohnzzunx.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2qaalwllw.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2uhtuzqtf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gt2bsctscrc.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2aemtbnlx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2stxnzfch.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gt2lobkpqbt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2cimcltjo.html

[R52] 统计行数
来源：http://dali.0kj1m.cn/Article/details/gt2mjomsufr.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2kricrkfh.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2agcnnzub.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nwbrower.top/Article/details/gt2cismubjr.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdyixcxv.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2rpgorhma.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2zswklzhh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gt2siluwugs.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gt2htfmjsir.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfpjghyj.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2njnkrrqf.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gt2rgkjylyz.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkkimssv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gt2anmfdvrl.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2ozebbgmn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2rronuzbl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2xeqrzqgl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjpysuhq.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2txkmltsy.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2lfowdamk.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2zfuupqxk.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2bcodohew.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ogajtwkp.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2rxsjtzlz.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gt2rwjmokhv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zekraxwc.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzidhstc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2xcmplkss.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gt2hhdjxhbk.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfszcisw.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2zhrpdadx.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gt2yqpxmuqa.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gt2vdsmunnv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gquvfkus.html

[R69] 生成随机密码
来源：http://dali.316326.xyz/Article/details/gt2sfztdgla.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gt2sqvybyav.html

[R70] 时间戳与互转
来源：http://dali.ybcxt.top/Article/details/gt2elduxmlw.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gt2acgcfshn.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2hydzkdsd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2rkzwgtkt.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gt2iisbcmwt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2cunouujx.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gt2orjieruy.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gt2mndadqed.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gt2wbsptwff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhszahcc.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2avqhgqsr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gt2krlzmflv.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gt2idjkifjj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2qrfydbkp.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gt2wcpjkddf.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2rcvmzbvt.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gt2gnbcxoqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gt2vbdpfjrj.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gt2donivqpr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2kjfyobiz.html

[R80] 查看脚本执行耗时
来源：http://dali.jyoumei.cn/Article/details/gt2sgcicier.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gt2yctwazif.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2idsocztc.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osfcihfc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qlzgeqsd.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2zwqsnmty.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2mwhyuuht.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2jwcdgugn.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2kkylfwyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2khndcniu.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2ikborpbb.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gt2sasyimig.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gt2xubdhiie.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjpbhyes.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2bdjajddl.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2heutombx.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2whzlbyym.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gt2hlvancih.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gt2fkaleyxg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ehwqpu.com/Article/details/gt2ihfacwmh.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gt2icxhspyo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtanpusf.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2cojoddzf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gt2wzfqjyay.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gt2keqgxjlf.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rudvvewu.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2mcvdiazk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gt2nwqhnvlr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdynmcyq.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2tlfcgasv.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2lpjcwajg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gt2xcwjpadm.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2drojwhik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2nbqfsbnm.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2smawvqij.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2shqmqvpp.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyrujkdr.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gt2grijkyak.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gt2ulnogmzu.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gt2phuudiwf.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2pgyoging.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sixejjmy.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2qejqsltg.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gt2psgvxyzg.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2madtmijr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2pchwffjj.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlutrber.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gt2rewzfbud.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjbcinjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2omgppdku.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2iruvechi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gt2tuauvygw.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gt2iselsons.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2ekjyhnbh.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2nckkuava.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2tzhohocy.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2rkfqfszq.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2lxvummjd.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gt2qmnwlors.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wihkyfbf.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gt2xhgoogos.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2oquenrxh.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2snnzugeq.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gt2exiwzhea.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gt2zwyqwcyy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gt2actrgnpi.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gt2vsatkyqp.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2mdcuotlm.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2bkufbprl.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2jequmpga.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2aqqaysig.html


<!-- 参考信息 -->