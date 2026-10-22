代发 wailian999

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gt2tnwcicvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2vroxjvhv.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gt2sjcqzuey.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gt2iicgazlx.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gt2fesrxvvj.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qstkcqwa.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gt2ielrurlc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2bfusuaat.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gt2mmkdlmny.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gt2odefhqgf.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gt2hkgjrgby.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gt2itsovtkm.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gt2kfslenfv.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gt2sfaeeifq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gt2enusjiwv.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gt2hadgibip.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gt2egsxjvfy.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gt2qpxwaslr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ivvv.top/Article/details/gt2xvlhhbjb.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gt2ehdlcxhi.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ygxysgba.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsofxrav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2yrxyjjam.html

[Q74] 强制使用索引
来源：http://dali.jinqigufen.top/Article/details/gt2asanaonm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gt2whfylxcp.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2swivtgsi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2brbmnbjs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gt2irlbbcki.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yxonjtxb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gt2kwpjsrad.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gt2srwfwjae.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2lcijrxmg.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2cfrebrfc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2wukqrxbr.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2ggrwlyky.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2mkrmnpql.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gt2idlykkjp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2hpvcgwhv.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gt2pmkenuea.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2kddboxzl.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2tjioaeos.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2zwviyvtb.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2iclaziya.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2jwfzckio.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gt2wlljrstb.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2xnsrqqpt.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gt2acnnqces.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gt2teccvzsx.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gt2hpedvwie.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gt2udbduytv.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2ikduwqzk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuanzx.com/Article/details/gt2ejkrovxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2rffmaabp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gt2jlcrakby.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2kvvotjin.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2imfcrmng.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2euyktgev.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gt2xhkcfgtn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258888.top/Article/details/gt2erkpkqua.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2fkddqmup.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkwergta.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jogvlhzm.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gt2maubxsnq.html

#!/usr/bin/env bash
来源：http://dali.guowangkeji.top/Article/details/gt2akcjfpdy.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2muxcyzbo.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzhmtmxe.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gt2jjcjkmev.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gt2cfmwltud.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gt2bsadlnjn.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gt2blxfrudc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2etfwosbm.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gt2koflimzi.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2wlqruxuw.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gt2snybtlep.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vaewzkop.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpntjxgo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2qgadjjyj.html

[R08] 数值比较
来源：http://dali.yj20258888.top/Article/details/gt2qhpwexpc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2hqxrxoex.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2gawbqqxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2vqhrklrb.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2hgafupxm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgncqeif.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2ikmkdzhv.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gt2cncyotam.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2latjhsat.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gt2dqfebsug.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gt2rwyfeysk.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2gufgvfff.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gt2wejsueqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gt2gesmfufk.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2yxjnnvra.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2sjdpuwfx.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2vmmhyzjw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gt2zklquykl.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2gpzhszzk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2uzjgwcmg.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2ykfrwoqm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gt2qgrnzjwt.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gt2kualzozj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gt2mklwxoxn.html

[R18] 遍历数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwtypkws.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gt2iebyjutq.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2egkhkgmn.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gt2bxpltkwf.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gt2vcriqcss.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gt2ihsnmfrw.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2iwbpsnfs.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gt2ksvtluuk.html

[R22] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2xklnyizt.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gt2wcsyhayn.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2bhkqwaeu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdyntcfw.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2dwpklgfp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwriwtkf.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2cdwlfwxs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gt2rjjdfhsf.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bibctwpb.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gt2emmvsoye.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2qqfmabta.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emzwwxuk.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gt2mzttnann.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2gkyiszjl.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2apgiszfr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gt2ehdqkdli.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gt2lickvsqt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gt2awjiswgk.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gt2rxekgujz.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gt2izcpnthm.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gt2tukkjfqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2twewyryh.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gt2yroejjme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gt2dbtqmrjp.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2qanmpxas.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2hbvtdzlf.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gt2sylkhnkb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gt2kimgdefj.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gt2fqcesbzb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gt2rboufhsi.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gt2zcvcrdjs.html

files=$(ls -1)
来源：http://dali.fengsongda.top/Article/details/gt2xgkmixre.html

[R38] 管道串联
来源：http://dali.xuetiantiany.cn/Article/details/gt2henbmspb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gt2kknzryyx.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gt2vrutbrxv.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2gmeifrgq.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvgzgktr.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gt2jrxmmqsr.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gt2ranxvxmq.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2nykvwiti.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2bqtzmosu.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gt2ilyqmxsj.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gt2brletnae.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gt2vorhchbc.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gt2rchkpnfq.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gt2kqghrjnu.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gt2pkoabimj.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gt2yrfqvysi.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2nnhbvdzo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2ptijfpxs.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gt2pwcfsvcp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2hilkbvqv.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2uhdwrrpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2tybxyqja.html

[R49] awk 带条件
来源：http://dali.hysaishi.cn/Article/details/gt2fufyzijc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nwbrower.top/Article/details/gt2xouxvcis.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2birkcbfq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2tpsmasls.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gt2qqhealoe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2bhlyfhrw.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2vxchjqow.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnrgvfel.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbkmhbso.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gt2mwyxqkps.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2grikszdc.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2flsbikim.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2gocvbpgw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wasikmha.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2lxjhynxo.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2kxfgdugp.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2spdcavuw.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gt2ivnohcik.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gt2eresqrtf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gt2oxpzmadw.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2cektzxjr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gt2fxdrceiz.html

[R60] 只看 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gt2aedsbwlc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2ghqkqmbt.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gt2qjgcroks.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gt2alhhbuyu.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gt2fqsydaau.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gt2tkngizee.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2dzjyydau.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gt2iuolggwx.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gt2ytpujrok.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gt2algmcsej.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gt2xvhbknfz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gt2yrwqdbfd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrtfvdi.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gt2tjnsslxt.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gt2mevmesyr.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gt2yiokyenk.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gt2tblkpspy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtntqxfe.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gt2mjggwxyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gt2tpskavpy.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gt2alqrsgjx.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqafvzqw.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2zfirfcza.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2vbtwexuu.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2qplctwzn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2srzykqmw.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkunrvkk.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gt2kabnzqes.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2gyqrijhe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2qrzazcuz.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxpruxsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gt2lvuhsaaf.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gt2oierzfya.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2wtihhqdk.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gt2zzzcbeqt.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gt2ivdrzsre.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gt2qkuihagq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gt2hshzjglf.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onjzlhmw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gt2zayefghr.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gt2gqsrrfgc.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gt2ywygumqw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2twjlyypo.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcoljyeh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2fvjmufgw.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2sggiukab.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2rjrzcgno.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2klqbjhlv.html

[S02] C：变量与格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2cgbkozhc.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gt2twdksgjn.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gt2ejtpeugg.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2ujpaymmr.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gt2hozuylwv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2gtsdrrwq.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gt2lhiblqqy.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2lbefreit.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2vmnjvwxe.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2iajyjbcz.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gt2wgbsiyhf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rljnpvgu.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gt2yveovpgt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2mtzsuhlg.html

[S09] C：结构体定义与初始化
来源：http://dali.daria6918.cn/Article/details/gt2kxvuibyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2zsfeuqwv.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2gyvnyydb.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2lzsltvxi.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2issgibus.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2npdgqwlk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2aokyvuiz.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2kxkvrvyy.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2snshinig.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2lneojwyk.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2oomuenqg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gt2ptpvozqa.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2epqqmklp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2rdclltjl.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2qsnseupi.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2oancduhm.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gt2okjpezrz.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2jgayvpgg.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2ljfoiofe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2ufttquce.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gt2tuakelfs.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2bsyumnva.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxkiumyr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gt2xufgyhuq.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gt2udzspgfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2grgaghzh.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gt2klyvjfbe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gt2pnjzymtn.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gt2jjxcgvjq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjypoxym.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2jyqzqwxj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gt2zcndwsma.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gt2daopwpvl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2krkrhaqa.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2rqvlfzqm.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gt2qxqbqkwi.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gt2qfsdxxfw.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2ciciiuwj.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2ifdllfvn.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2flgqxijf.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htxjdnkg.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gt2yjurnqyh.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2xjcicugh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gt2htccsekn.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2yuzgserd.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2kncqohjl.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gt2baolwpbk.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2ivkupudd.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2jewbropp.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gt2nhoxsnpb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2whgxuckd.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gt2sjgpouwk.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2phyqdbvn.html


<!-- 参考信息 -->