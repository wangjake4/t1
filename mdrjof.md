代发 wailian999

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2dcqawlsw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2tfludieu.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2nmtpsxxl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2gxnorogg.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2qxepmmwr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2hpfuqptx.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2jymtfvoq.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gt2jprsmrge.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gt2pcoskgia.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gt2wnooicgv.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gt2dxlufsbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grqyriiy.html

[Q67] 设置隔离级别
来源：http://dali.tanke756.top/Article/details/gt2bbdfioof.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gt2jrxrdjcs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nheikmgp.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gt2qxnllvxx.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2innmglus.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2zmrafxni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gt2folgmnvv.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2udtcggrr.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmpoedww.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gt2qdifjujn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gt2ykhscvzi.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gt2zmtukkmf.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2cbbblkbp.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gt2goaqgtub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mteghbfm.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2qybblnnq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2tryjxvwq.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gt2nwwdbzqw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2rmzvthbe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2fcvpwylu.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tffnpgfc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gt2ifxrnhui.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2ucsajnrb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2cwxiuusa.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2moyeyaut.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gt2rdojluks.html

[Q79] 字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2qihzltxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2okhdyinn.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gt2yflmpbmt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtnoozuu.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2uxxsufmh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2gboyuasc.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2jvidafax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2jinmxatt.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2sfoxmlwp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2sqvsxvaz.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqxtktbn.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2oosjrunf.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gt2iylrnqsg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2phagzatd.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pktdedba.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2qjiyiuzq.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2jdxsggjy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gt2kokkbdhf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2xwxlsknv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gt2dcgzgsdf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2uhlbmfpq.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkpfjfui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pycfn.com/Article/details/gt2tailruot.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gt2kiothpws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgufenzy.top/Article/details/gt2xbjiokip.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2diyqpklz.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gt2xkujuzvh.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2sbccxvtv.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzbjslzg.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gt2ghscyjka.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmyibbpd.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gt2hbkcxjmm.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnmxbkyf.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2angpqrse.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2sviydivs.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koflkppx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gt2posxejtf.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2fqjrccas.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2ycrzxceq.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2mcrcowew.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gt2moqtdnfw.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gt2jlxqttoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2qiugjnpj.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2bdqktbhq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2brqnfsxk.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2liunduxh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gt2sheaqqld.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpirusno.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2omhfhdcy.html

[R11] case 多分支
来源：http://dali.sufxvd.cn/Article/details/gt2mbmufbdo.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxyazknm.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2tcotlump.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2pgbuqlkr.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gt2hnfrztjd.html

esac
来源：http://dali.yonumen.top/Article/details/gt2cvuzefpg.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2qyrgmbyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gt2llsxroai.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2fxmudtwr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gt2kiwrjqbj.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2gpggkxag.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2avltdrzk.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2jacguboe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2krcgznuw.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2oisbdqiu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2upasmkga.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2vkvlmzkd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gt2ofphxxio.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uymhkwtw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xffapfpd.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2rftuxywc.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gt2pqfpucrl.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2lgqrillh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gt2wbacanci.html

[R21] 字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2zdpxbouq.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gt2ocpixrcy.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2kzfpdkhe.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2gqribnsh.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2tncclhdx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gt2zagkknfg.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2lhchzwla.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gt2gagkbfwx.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2pttsdefd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gt2hijkbdhi.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2yrwgjkmb.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gt2dlfbjkeb.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gt2zyqmenab.html

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gt2tscozwib.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gt2fxxiffwm.html

echo "scale=2; 10/3" | bc
来源：http://dali.vqdsnc.cn/Article/details/gt2zywfvjhi.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2uiwnnwvm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gt2kupmwoip.html

[R30] 函数返回状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2picqjafz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2ibrqprgy.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2aydvytot.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gt2emasbjay.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2hjpsceon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2qsyamnta.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2iiqqmvxj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gt2lvnfpnhk.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2qvvogbod.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2iduopppo.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gt2qbmtvzod.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gt2nqnqvqjr.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gt2qrozvqha.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2ftlinntj.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gt2cvbisuhv.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ggmbcrua.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gt2uvqdutmh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2yznncayy.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gt2mdqnomhs.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2mmakjrtr.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gt2nmlhqypd.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gt2veoesyxb.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gt2ytalctgz.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2bxbusiwx.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gt2ewnqdrrz.html

wc -l < a.txt
来源：http://dali.ivvv.top/Article/details/gt2hbcntxux.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2fuvlqpcp.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2gbhmcllm.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sexiinod.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntgkwxmp.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2rkwqujiq.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gt2rchrdlqc.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gt2hynvhqmm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2flgfdsda.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2wnqsgwbj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2xevvlfvc.html

[R48] awk 取指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2pqbzzxgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2boncvdsn.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gt2ibtfmmnn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjoxontb.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gt2ukmgvewc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2umhfngcl.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2gwfqtuun.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gt2etbsswqd.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gt2azspxyij.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2fsdzrcem.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gt2gxxnmbvc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gt2rkdsbexq.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gt2nttihjvn.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gt2imspzkuh.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gt2fblwhecq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2dvakrpdj.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gt2pynyttqx.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gt2nwdihflj.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gt2vzexdgnj.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2hogwryip.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvyxbosw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gt2ielsikqw.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2lbwjuvvd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gt2yclgrxjm.html

[R60] 只看 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbeimvyc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gt2zoqurpam.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2sfomtkkg.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gt2viimtaxx.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2oonoadqk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sesshmgx.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gt2savnuuck.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aezyfbel.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2bwaauckv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gt2csehvrgh.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2lnbgwqtd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2nzakgown.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gt2ormnivoa.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2tztsiwif.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gt2hwjroolq.html

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gt2cbzuqktq.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gt2xnfodhgy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gt2kxhcxwwq.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2hjamzsxe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lizgiimb.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gt2tlsioedi.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gt2acifpgsr.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gt2venyckzc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2rcrlxccp.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2klvopzca.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gt2xmshtjjv.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gt2lgmvtqeg.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2qsgxeacn.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2vntktahk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gt2mlydmpgv.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2gtnagveh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gt2vifgtzqz.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gt2lpgynsao.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2syylhriy.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2niehslrn.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2kecasbiy.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2dejdkafo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2bqcdkesf.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2pblfbybw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2xboufxhc.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2dpjzbmmk.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfwbfygz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jdqyozza.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2sueznsag.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aardtzbw.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2qvcasxth.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2vpkzzynl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2cqzvlqdv.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gt2axmhropp.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gt2dprzvano.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gt2jqmdcdch.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gt2euahkrrw.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gt2qsvrstqd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gt2pqbgftno.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2fhlxzagv.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gt2wiholdek.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2yckgiaen.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gt2jzvwrqio.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gt2uuuzuatn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2pepplxma.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gt2ckvdfmuq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2bwklbiij.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2cnynzhnd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gt2aegbgqog.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2wnuxppgn.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2lduciazb.html

[S11] C：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2simiyoid.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2yolrrqxn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2rokcvcic.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2szdendqz.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2flbzphli.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2mxcrmmab.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2uatmcqwf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2hjwmutpg.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gt2ecwsikdr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2qtwzrduc.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2rymiwnme.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvxjacpy.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2lzczfjkt.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gt2vukivjkv.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2eozdswlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gt2ipanaysy.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2qoufykyw.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2flcaroto.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gt2kjeezrws.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2girpxvys.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bikvorfs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2eqyvpfle.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2dqjxfkvb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2hweemepn.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2annlsdvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2jzcbsswx.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2oyqaedru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2mddpcbpa.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gt2mconnuza.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gt2ibbcaaui.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2dkgkqdqq.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gt2unfkpnlx.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2eujxynwp.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2suloywpx.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2lvkwytlw.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2vdlqizyp.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2ymacedbm.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gt2wodbxsvs.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2fuxmrfjn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gt2gzzsegcw.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gt2bkvhdwre.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuxzjlei.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2wbvjrbmv.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2pdjygudy.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2opifxxpu.html


<!-- 参考信息 -->