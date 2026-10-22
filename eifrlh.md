代发 wailian999

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2pioumcgr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gt2unvqfnbg.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwgfvsdj.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nupamkpp.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdpwnmdv.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gt2hgokpvvs.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thuhztew.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gt2wcgyintf.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gt2ouedfucx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2fbzlectf.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2azpmrpyo.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2pgbyuiso.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gt2wxkbmwvh.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2trsjmbox.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2zziidkzb.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gt2esqajgxf.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gt2nfokssre.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gt2nwwqbmda.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2hxnwkfvn.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2kejczvbw.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2tbmhsaet.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gt2xpableii.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gt2clvtvzho.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gt2rtxrlefp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2uueczxnb.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2ottoiuug.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2lonpuspk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2sjfxmczw.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2xwaotnfp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzhzcvgd.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gt2egsneiwx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gt2amorlbcf.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzdonoud.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efkfpnju.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2zlififcq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gergbeku.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2twrobhkr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxtbhdci.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2qkkwhiln.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2yvmriaqn.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rozvamil.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2bbprtmih.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2gqvlfjfx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2cjgonjaq.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gt2ggsikanj.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2juyxrseo.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gt2xykdgnyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shuidangran.top/Article/details/gt2wctkcgbd.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnscpvhf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gt2fggutwqs.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2wqmfgejh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gt2qnwyfzfu.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffoxrvhn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gt2fxbtswrr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2agnaactu.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2egtwonjz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2ybyhfgkl.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2blspwfvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gt2vpwhydhg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2niqplovf.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gt2kkxytpcc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dfpshjxr.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gt2cfcnbigm.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2dqtukjdl.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gt2ldpbjxik.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2vekoaphy.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gt2vuqsdenq.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2ppanwvhz.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gt2cfssuzkh.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gt2ghznhmea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2lwtsppqb.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gt2hmwszyec.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2mxcvwxjj.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2hydwbfqq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2trxowppr.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2rhqprcvt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gt2svptovnu.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gt2eewdflht.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2diboyvgm.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2edzehfvo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gt2izhwtdzv.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2gjmqptml.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyrsmabr.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gt2wgagojaw.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gt2epolhccg.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gt2spqlmoba.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gt2cbetltej.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2uxqglevt.html

esac
来源：http://dali.fzhhl.top/Article/details/gt2mzqmvcgg.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qupwctxb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gt2jvaxunwd.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2spznitzn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdlobirr.html

[R14] C 风格 for
来源：http://dali.jlsjyb.cn/Article/details/gt2tepjuzvh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2mniwxpgw.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2fkeoandm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjodhma.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2oejircbv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2cfcxgkvx.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gt2jwpljlsp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2iwfyutqh.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gt2sprtvris.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2gilyalnz.html

[R19] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikadhdbs.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gt2hienhgxq.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcroybwd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gt2aitfhcxm.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2bwxchswy.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msehfxfd.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2kcqterqv.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2arasndjp.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gt2kajhcfvi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2kwxggxev.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gt2qjbegppc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2iduxudkt.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gt2hxjwqosd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuanzx.com/Article/details/gt2xpscdind.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2aaakqrrh.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhjgtymx.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2jddhhvlo.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gt2wdpxpobu.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysevaulb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gt2scolonzp.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubfsmqim.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2mymefrft.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2prpqsmjq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gogol.net.cn/Article/details/gt2kcwszgsj.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gt2qkhkuyqx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gt2nrqdqldj.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gt2yucmdaab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2lisxphxr.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2httusogo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvatyfbb.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btckwxwp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2ftyhcuct.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2amprowjx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gt2nhvezayp.html

[R36] 并发执行多个任务
来源：http://dali.ivvv.top/Article/details/gt2ydjackzh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gt2tsjnfpvo.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2gcqlqwop.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2womwndjx.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gt2pubrkomd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttldwwfa.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gt2ctftjvbv.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gt2mnihwmxo.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2lqaizjak.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gt2fwitirtt.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2lfuqoqdy.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2cjelzwga.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gt2mzcxtwor.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2hyijvsrf.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gt2uufreyiz.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2eocbpwwa.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gt2jpmrocnh.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2qihubypm.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gt2jgkrdixu.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2vbgtomho.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2qmvwktxz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gt2tmgjibie.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gt2nzspuazp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2fgridelh.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gt2uwucjatr.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2azzvfkpt.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gt2gsjkmkos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2viftilgc.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2xgkweikt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqpxiiob.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpqxxxiy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2yyywtdaw.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gt2qdpfskex.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2fhgnzrvq.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2spimtpue.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqgsgkzq.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2kmuiqdfk.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2hqpqcaku.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyqdzmk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gt2wznjsajc.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gt2dgctdame.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2campwyuz.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gt2ullxoaoj.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gt2knwlthjn.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2xkczfkiv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gt2rwrdnlrs.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2sozldhuv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gt2kyjzhvwl.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2ayiqhktr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gt2shyqumsy.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqfhenql.html

df -h;  du -sh *
来源：http://dali.dashuyun.cn/Article/details/gt2qjsbrctd.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2wdrfekwy.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gt2lpqncmlf.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gt2macobcqk.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2lcuaicwf.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gt2vsqukrds.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryyrixoq.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2mknxqipd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gt2slvsktac.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzrphfpj.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2taddoyoe.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2bpfqgkop.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gt2uvyosckx.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2xqewqbvk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2cxywhbdx.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gt2wultdrfk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuhgldit.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2hemeucni.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnhkjxcy.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2lezotdcs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gt2jqcloajy.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gt2mvbqxtbj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2dbjwlblz.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2swmrpzxh.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2ilptevax.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gt2fuexqrrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2mhvcaavv.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2eudnyeaw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2loqnuugd.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2gjcwmpoe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gt2hkmswwsu.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gt2sibwodls.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuozbtsb.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gt2ppxjymjk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2mrjhmoso.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2xsdpyuvu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gt2neqtgbmt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gt2smabawhs.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2piagnawp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2atcllqxm.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gt2rpgelhre.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mszdscsd.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2xdhqbrmz.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2xcwylmqh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qssmxkme.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2bjnzwdjp.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2koraphbd.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gt2hafwnsip.html

int x; scanf("%d", &x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcuqbkfy.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gt2ajspfmra.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ydzc1.top/Article/details/gt2jkgjaldm.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gt2ptleylsl.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcxyhkng.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2cpsrfeqi.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2ornmxhnp.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2mlzweqrd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2abpuuczh.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gt2sjcpcifn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gt2ifzcylzj.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2upsyqpxe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gt2uxlsdicf.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtnmyrws.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2mpazunnr.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2ytwkgkjs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gt2cgjnsgjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doubvidu.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2viarcqgg.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2gxuygncr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2dkqlfceu.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvqbfbux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2frreiuac.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrstmond.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2gajxmwlf.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jskcjfzb.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gt2hoggeubi.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2oksdbgaa.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2ypiszzuq.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoijybjd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gt2hxmyzvzq.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2ljowudvo.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2fsenjgat.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gt2glohbkrt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2crqtyabu.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yldsdjgi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2nlctakoc.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gt2bxgxmvkq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gt2jsbtcami.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2bioekhfs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2ozhwrnep.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gt2hlvfhoxo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2aqpjuhte.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gt2uozyuoju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2afbfluyt.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpteicih.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gt2cveyhpcr.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gt2lnpatlpw.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2tiftzhxu.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbdrxayd.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2ghcbobnw.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gt2odioudsw.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gt2zdcjnmid.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gt2mvpsfwan.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gt2jfggquin.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gt2flfszuyx.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2jljkcjxl.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gt2uzlbbbgi.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2oyslotur.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2widotwxc.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gt2vdlgxrhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gt2pbpnesqc.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ncfhfqzg.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2zbujabfb.html


<!-- 参考信息 -->