代发 wailian999

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtlqbznlbb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtqrukdcde.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtqgaycguy.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtoicnloip.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtxexizwqv.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gtimukselh.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtockgefdd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtqsghnplu.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtztwocclo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtmjokoiao.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtujxyfawv.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gttcmvxlyf.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvozdglt.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtmiawclum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtjwrupysu.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gthbpyjmgv.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gttflwxmej.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtdlcrxpsp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtomkanlja.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtzwqgcvll.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtznuexosn.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtegdybvkf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtlouepjvv.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtvegsqagf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtetqarlsa.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtxqcrhvxh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtnriznqlg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gthgmjmthh.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gthlhdudtt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtvavadaux.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtzlavblnj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtllaeyqfb.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtlvsurjjg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gthjubwwht.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqrvhkyc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gttvmxeufa.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtmnltvspe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtprxlqekc.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gthpbtnfxn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcsqvrbzz.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtuhadvxpe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtjycbegsn.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtmiwpzwcy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnahbfhyr.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtuyfrppyf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtlwyuexri.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gttqvyamtt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtgdpvdjvr.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtwfcarylo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtfbvcmhfo.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtfnyhsjph.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtdomfupuf.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtbpmifgzi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtmbctzifs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtduuwvccq.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtgqxrskzt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtokvkwvdw.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtkrfqezqf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtnprmjpcw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkcmvmgik.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtefjkcxok.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnigkajcp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtnumimvea.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtndshwtpi.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtywctudmn.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtpvuapdlb.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtyabiyhqn.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtudmqjlvf.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtkdnrsmmo.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtgrglcrup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtixvknzuh.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gtzplpeclo.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhkuyxwa.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtleapdnxo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtitovrzab.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtllfphpqh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtvjbsvcun.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtdjdkbiit.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gteenmaxgi.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gtmfroqidq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gtphogfavs.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtwuhvkhod.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtwtvlvxgp.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtsmqiruqu.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtcjrfufkm.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtdkymxkjp.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gtidyvgiqz.html

*)     echo "未知命令" ;;
来源：http://dali.pycfn.com/Article/details/gtbulgdaxw.html

esac
来源：http://dali.gzhubu.top/Article/details/gtfnbntxbg.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtxiemaexb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtrzsflpjt.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtqvhuifbq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtmdqfrmpz.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtmusogxtr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtspohrlpq.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtrfxvkvvw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtvhwtvhds.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtyoorewwr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnwhcakn.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtmiwvstfz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtzigtnisi.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtpuqyqlpi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtfzqbksrv.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtzmxuvcdy.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gthkvozljg.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtykezlfgy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtlxkxqbpd.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtetyeskle.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtzjtfwjio.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtewxlkwpp.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gttzgborky.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtfplqdsyl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtxwtyxtdb.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauohnfrn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtfpyqymsn.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtejrmibto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlykhqlxq.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtreegrczo.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gtcjjtjbiy.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtnmwcbzwv.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gthgqzcdni.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtojfkpgps.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gteqgfqfns.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtilbsqgvj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shuidangran.top/Article/details/gtobcekits.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gtrvistxtt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtqhxcwaxy.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtjimmepsa.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgbvvnoiw.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtwwijgaka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gthjdtzser.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gtzkecbklc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gogol.net.cn/Article/details/gthqsljcsq.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gtrdifghqz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtjwbewvwt.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtozyngmnw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gtsirmwqyy.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtfyofdanr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtbgqkvxyb.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtloivqphc.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gttubcqopw.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtesrhbigp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtfrjxpuqj.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gthtkrvgyv.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtwbsoexss.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gtplsptdne.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtovoatqcr.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtvmvrlotq.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtcskbkmuw.html

[R42] 输入重定向
来源：http://dali.jqgufenzy.top/Article/details/gtwklmuacn.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtsgvdzoeg.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtbjvafhss.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtbxzbopnu.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtiykzvipz.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtcyrnrsyp.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtsooqeoao.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtuzrmbtvx.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtrvgujmek.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtfgiracse.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtkucgmobi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtbbugziwg.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtgnexsqxe.html

awk '{print $1, $3}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtmsnksdkv.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gtqmskdblj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtgvfkdore.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtuftvdzbf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqywruvw.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtkrvwegod.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtqcgpeaig.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtmbfstfdv.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtdxhernhk.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtffzsbvwu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtqnjouclm.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkjxpcbh.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gtezcocack.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtnltnmlkn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.kuanghao11.cn/Article/details/gtxnjvhwrm.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtcvlcgjda.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtfvlzzsrf.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gtekzxivcs.html

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gthfrmsdqn.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gthndvtzpx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtmrvnqgdf.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtxkbhtyry.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdlzyuua.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtqsczijkv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtkrudrabk.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtbamqbeco.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtkveaftgw.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gttokxzlma.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtizzcembi.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtxsnpgwzl.html

free -h;  ps aux | grep nginx
来源：http://dali.guannengcc.top/Article/details/gtigfvbspu.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtuqmvudwg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtqbxdocux.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtwqvtjiwz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtzaexopcu.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtqghytznm.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtbyignqex.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtzwpxnnos.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtwatemxug.html

[R68] 计算文件校验值
来源：http://dali.pycfn.com/Article/details/gtxopbarun.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuendfjdy.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gtwnvurqar.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gttsiqvujq.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjwtplaj.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gttbqhxhbh.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtvthznwii.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtarxzlxkt.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtrxxrymhm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gteucymoes.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtrjcxrxit.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtdqkkxbpk.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtqrniyhon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtihmydlvv.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtgbsubdaw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtczkbwpmv.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtpbuimsev.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtvxovxqdo.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtqscwnnah.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtygmzduur.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtktxyjvfn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtufcsfdrx.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtqbshypvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtahxipcxu.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtvlhvppmi.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtioquoyla.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxwyhkeaj.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtokxxjhwe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtygdvmpdw.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtkhegfdrs.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtyplufqxy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gtluqhjpqd.html

[S02] C：变量与格式化输出
来源：http://dali.xuetiantiany.cn/Article/details/gtfkqbyljv.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtmypxjejw.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtaflgbugg.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcnsijuh.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtxeemimnh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtjrhjskwm.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtlgbuqqoe.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtnkmaeixx.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtulcmdeaf.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtbormtnfa.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtmnzvzmfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtiaqumlzo.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtfbomzsql.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtezeosraq.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gtplkbvxhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtopyzqxco.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtcbzvwmcw.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtzsuqhusd.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrdyldlr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtxcwkjxzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtngnwzpdn.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtadtrrpov.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtdsjhcwpx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtqrprdovd.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gttgyoqkvd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtbruekfom.html

[S14] C：枚举
来源：http://dali.daxiang520.top/Article/details/gtetdgjbbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtyoqpiqjx.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtflwughfl.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtaboxjgux.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gteeejearh.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtqafpryck.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtacrrmjxd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gteqzkeqbo.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtzwqizrli.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtmdmbrktv.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtsgtskhiw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtjkcqqdnd.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqugygbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtvcdzefrs.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdskvkng.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtecdfjwrc.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtgtcdvlpf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtpcwnvhyf.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gttlgxfluo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtwhyzfiee.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtyfousoqr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtvoodsuue.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtikowmcbx.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gturbyokvd.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtmrsoxnde.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtpccqvafs.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtxrrzjpey.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtjhokzjoh.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtmaskgabj.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtucllzcze.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtgxmubhau.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gtgjpssmkw.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawrjdxkw.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtihbkjqfr.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtlybaclcj.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtyusooede.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyxxbivn.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gtaotewktm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkklymdtx.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtgmsmyrre.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtngigjxgp.html


<!-- 参考信息 -->