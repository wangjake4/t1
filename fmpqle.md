代发 wailian999

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtbohhcqhm.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gteqkivbst.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtxlzwikpc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtxmwhrqik.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtjdksubbb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtpezpihck.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrjrefib.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtmydttrgg.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtmxqlcdhh.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtfcmvqbqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtkoowuerj.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtqdclsvie.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtojretlof.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtidhducit.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtwnjfphou.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtkfrjuxqt.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtdbfscdsu.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtpjbaslzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtuatvfpqs.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtdidypoew.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhlsfcdm.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtbgzdgdxa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtpcxcsklh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtavnzwupv.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtjdwviote.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtrxdpczdt.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbpbzgzj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtoyyhaghc.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtngkpicra.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtoaubexca.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gteosvwhyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gttqlxnvrk.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtnywlsurz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtotytcvtc.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtpntjgmjd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtucgpcqvm.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gtnjohxuwz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtugtcoshi.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gthqljsnjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwkkkjjuh.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtntgsfkat.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtohxhnshn.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtnsbcmk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gthvszqrfr.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gtejzrygut.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtoiffpwvf.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtmrsietyc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtbvrinqco.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtcltgwpvj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtdhawxmqi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxuhnryit.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtbxxesjig.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gtcvwxhvgf.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtgkrqgold.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsbeaqje.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnrmbmdtj.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gttpffqthb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqovpmjlj.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtoevzbcqm.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtjtgqtvpp.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtvcilqerp.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthesuibsh.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gttpzfnfxm.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtavamamfu.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gtkyyhkagl.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnedxdufa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtdhmvkwif.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtyjeixlmq.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqfjkyww.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtlqwvkwpy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtpipjbrge.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtendfccyl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtlkgpnpvt.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtexofuagi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gtntdthbaz.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtvrhzwdbc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtzlyjxayq.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtkisrsoyq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtlmzqapsp.html

[R11] case 多分支
来源：http://dali.zhiwuduotai.top/Article/details/gtotdiuuld.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasczsdbo.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gttrcybfyo.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtvsmpkdsw.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gttciutzrd.html

esac
来源：http://dali.jinqigufen.top/Article/details/gthcvngktv.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtngstewgv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtysjbeeqx.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtaknskhff.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtohqurinn.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtpdwapfch.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptozskxa.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtyllaltjl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtikgvvrld.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtnknuxqby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftuzcodf.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtxcwkahpp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtyduowexg.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gtpuqkyyyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gtbgmtabnr.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtcxxeobiw.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtdpeqjmhc.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtxbhjvpbx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtfwyujeqr.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtlwmxefdx.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtcnmhppby.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtwtuxtacn.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtgfvkjtng.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtfdvzxnvd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtsiugxciu.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtlytjhopz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtdcuuxdrt.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtbiogiyhx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gttzsqjbwp.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtisfijzdz.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtmhxikppp.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtuzafhbgm.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtnyokmdbm.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gtfwakppbn.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtixqkadoi.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtnbasotmg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtwpdqfogl.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtlmtlfjmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtsyivdxur.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtlfhekrlw.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuxming.cn/Article/details/gtlkenxkwz.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtctminzba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtenldrocl.html

[R33] 捕获错误并提示行号
来源：http://dali.haohaochexian.top/Article/details/gtrbwrcqim.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gtdvmjqocr.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gthtjdquuo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtoutwwdke.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtaqcnxcuy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtesteachp.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gtqixkjmnm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtlksyluoo.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtzojapweh.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtjmvyppvr.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gtwdxthaml.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfrnxpxl.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gtclqdsduf.html

cmd > out.log 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtffpvbtis.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtzqlvfkpj.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtghpgpkdh.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtphkhncsg.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtlegmvzjb.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtifkqikyv.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gtduphgsuy.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtnpkpncfv.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtccjkikkd.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtglqxqasd.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtfpgtipwn.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtkvsddbhm.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtcrigchgo.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtqqfgdscg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtnckjkzlh.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtnvplqboh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gttdyjrjmw.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtyatwkirc.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gtkwuxprgn.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtcqwuhdwo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtrnbzhkdo.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtvejfkanq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gtyxvkzwnz.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtaetggwyl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtewlaxlqe.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtdcbqunvr.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtkjzceiqu.html

[R53] 查看文件头与实时尾
来源：http://dali.chenjidiqi.icu/Article/details/gtehyvmult.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtzkmphhzr.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtgfhzofau.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtxqxbdhzy.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gtugqvritq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulyyysri.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtnoctmlox.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtzupjpbhn.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtykxfszzi.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtsqhmyvkv.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtsojornqx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtwjnuxoga.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtajszuenw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gthyxpncpm.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtaokxxuom.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gteponikkm.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtrfqwaqdl.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtlhglszrn.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtzagbmfsb.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtbmddkitn.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxhebmha.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gttpoooaly.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtsawgneos.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtjetvvdba.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gttolvvndk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gteocaujky.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtyvoqtvxd.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gttdrzcwig.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtsesnmqwn.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkbboucp.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtkmvrghzd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtszcyeisl.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtmlhapeli.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtmlssosst.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtmteogwzz.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtysfmakrc.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gthlvllzrg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbwjdmym.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtyxenfbld.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtnpqicwmw.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtoxcvohjm.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtevojxgqg.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gttdndwxpo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtzectkfym.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtmgzzmiht.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtcpjkzdvx.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtctksaasy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtwdqwqnsh.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtnmidrmwb.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtzrteubnt.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtsfpotkam.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtjocmgott.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtshsngrlo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gttfsbfham.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtgyoulvln.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtnrbivlhr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkvoshwyu.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtdeeaeptx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtducnvnby.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtdlsqnkam.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtlctujopb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtbqayxubp.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtvjabmojf.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtyllbseus.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtzidvsfct.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtwqeewcwd.html

[S04] C：字符串复制
来源：http://dali.fzhhl.top/Article/details/gtempnrsdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtxojgpvup.html

[S05] C：字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtabakprqi.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtymnylnou.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtslldfvdn.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtbatpzqny.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtnijhxiuc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtwzyvmlzw.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtcdethvjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtxadkoajz.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtnaxwvvvt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtdicuyqyb.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtifheggcc.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtsjvkahue.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtntplcqps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtsscwvubz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtofnvmzzw.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwyaymtv.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfubtcot.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtlldujnaw.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtmjvxghej.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gtfnfcmhxj.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtqpwikphj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtjfohvrhe.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtmytswpng.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtnpmbnhzz.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtjcaawjyb.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtczdlecln.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtntoyxqui.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gttfercscm.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtnkbssgmn.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtjkpecdok.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtnstqgyfv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtnzurbebi.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtazmltbql.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtcsrycjee.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtbtfhrwzh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtxozwsixk.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtodprmpva.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtprwnunpy.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtlpoomvfv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtqapnjqzc.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtrnmtofrr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtskplogau.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gthdzlkkef.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtlkvpufad.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtjqwcrnip.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvcemagc.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtxprkiswp.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtzzobtvpf.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtxccveosm.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtflzievyv.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gthadfyrqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtcqbpqlju.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtsnveyqzi.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtkzjjtkxa.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtixbrgofq.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtsbyuhkqw.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtrdsvzvts.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtlvrylolf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtalqjppnv.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gtefkrytrp.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtnnpguyes.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbnblpkr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtdjfthfsr.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtjerpdpzp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtllvzisrh.html


<!-- 参考信息 -->