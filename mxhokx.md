代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjgubftq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtsiynwhhy.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtbasbdhyy.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclnvrjho.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gthdrijvlz.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtefwnmswt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtdficugsu.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtfsqwlfiy.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtiofjhsnc.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtvkeyypzx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtehkjoomh.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gttffmnqyc.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnhtliezs.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtvvlrxldq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtwwcvrjkp.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gtoxmsfvhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtgyaggihg.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtsoohhfre.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtlvtqsetu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtfgfquewe.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzueqipit.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtzmphgvzg.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtzedqvdqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtwqofklkc.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtceqlibsx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtzzhebqcg.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtsgqooalg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtniwzzkgf.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtulnnmrkc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtupbloeez.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtkcgtapgo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtyaqptkpc.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtnapjenic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbksacyga.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtnnsuywdy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtaqvykjqx.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gteinrquty.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdpnhffop.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtpyyeqoiv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gthxqnpojv.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtapoeondg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtxykstytj.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtfwozwfgy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gttkgsnulz.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtcbsxspnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtmbjewmsp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtqnthonqp.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtdfjtcltd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jyoumei.cn/Article/details/gtncwdtonl.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtixwqnjvl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtwesovrnv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgeokwgxv.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtaojmykis.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpxmbyowc.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gthejhwdao.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhkdstab.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtfvjwpttu.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtlfagggip.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtsvmqwlap.html

[R03] 只读变量
来源：http://dali.jinqigfzy.top/Article/details/gttuemifjw.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtazluijvf.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtyjibafhn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtsceoyavs.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtiorwmfdd.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtlfqgswgu.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtqrodbcwo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtfwzkrzjc.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtoagwalod.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtmahwpbmq.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gthmjyffjp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtsqsupllm.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtrqmxxhdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gthvpsgere.html

[R10] 正则匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtrsvqkidm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gtvqsyvxhk.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpcstrdj.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtteabrpcr.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtucmvcpri.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoopvbvc.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtbloskazg.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpxgoxby.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtzyghwdyl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtjwogpitw.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtvihrtfxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtdmhsnhlv.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtldsblwul.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtojvmntot.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtdyowtvtw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuxming.cn/Article/details/gtbfzxjinp.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtymlpahoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtrrleuief.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gtbjdrqtck.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtfwjpcvhs.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtnhffwosh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtpmxithtn.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtkwddgicw.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtwmzcyhjx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gtsxhizyyq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtnkayphzv.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtjgcxoioa.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpntkywg.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtrqxdxnbc.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtdqtjgoqp.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtekdepmqm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gtdhzxtmys.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtpiwdqvta.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtuznlkzql.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gthokwltwz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtpgqsyjqi.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtqmnxsrrt.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtdgaebhxh.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gtnkikftky.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtiivnfbjk.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtddblxwsv.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijzlgcuc.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtuwtegzsj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtwkxunkjh.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtkhdmqhxb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jyoumei.cn/Article/details/gtpeqllkdx.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtlfoqxduv.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtoffmodag.html

[R32] 参数个数校验
来源：http://dali.hysaishi.cn/Article/details/gtxmnmcvep.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtwfyxqchr.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtbtzjhoep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gtinodzpau.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gthzwmifgq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gttlmbacty.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtgtzwvosj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gtpwbrhall.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtxynxzkii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtmiqqkwzc.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqvtdxav.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gtswqrzade.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofmhxjsu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gtbexmiogu.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztpemkid.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gthveuknpy.html

[R40] 追加写日志
来源：http://dali.wangshuangyany.cn/Article/details/gtjhzgncqt.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtbnjsvwse.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtccbjloiv.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtfqahfafl.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtfttdsnlc.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtuvphfz.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtqhjmuztz.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtvwrhzeiz.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtbqygczdi.html

find . -mtime -7 -type f
来源：http://dali.pycfn.com/Article/details/gtnfkzssqy.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtmfjqxbli.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtuzlxctax.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtybqdorwt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtbrtgkjox.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gttjkyaaox.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtlhsfrorg.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gtwfvcydzh.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtfpyrbdkh.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtdreyagcu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gtkppmszqu.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtwraxwcsg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtywnioyrq.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtmxrmdwnl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtegllqwsx.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtmikougey.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtzsxuljzn.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtwnknmnut.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtbnztgnaq.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gtjqwdnvvz.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtpmtfeacm.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gtysayjoet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtconvknhk.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gttjctrvwl.html

scp file user@host:/path/
来源：http://dali.cheryme.top/Article/details/gtdimvlrsp.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtmipsevjr.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtrgamqzth.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtzybibwoc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtkcnqiack.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gthlrwhdwu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqpeomak.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtkolhhugr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtwunzknwi.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gthzlzavfv.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtkielvjob.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtmzwsnbtz.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfsthwtk.html

[R63] 内存与进程
来源：http://dali.nwbrower.top/Article/details/gtuvwgvisu.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtryyvtscj.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtjoejzslw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtyobtzekc.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gteegludwg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtcosuqxwl.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtmcrvqxry.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbkwikkd.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtddtvkwmh.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtupoicxab.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtthdfvznk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqwkomaq.html

[R69] 生成随机密码
来源：http://dali.yj202588.top/Article/details/gtionydyup.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtzvfsrqtz.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtlgwzajte.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtprblxunm.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtxbrlqqle.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtlmlkrdlo.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtlnduoyhy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtuyhkemfa.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtuovyiscj.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtcqnnvwxz.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtjlsvhokt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtujafsboo.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtadlzmpeb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtucoiilmj.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gttevxctzj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtqzjnkdql.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtbipwyhfr.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtbjmmikga.html

[R78] 交互式菜单
来源：http://dali.wangdashe.top/Article/details/gtedgozgae.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gthogoussk.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtnhgpbmtq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtwoqwjosr.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtjdigkbev.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtrsdbhgou.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyjcixbfr.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtjchxuiso.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttlzrnein.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gtvbucfyds.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtultwkldb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtikhuwveh.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtlvzexvgc.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtvqdyflxq.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtsfrinjda.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtxxnecjna.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtjukoezbw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gttjjynneg.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtkcnvmjdv.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtaoknudlv.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtseadzucv.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtxgjkhaau.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtbcbzjzzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtscjrcqww.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtvvsohzeh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtfigffpfx.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gthqehcjou.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtbxqntkzh.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtelecjwlp.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtremlctsj.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtdleweexl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtzpozhhwx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtgkyvqxmq.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtzyatvudk.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtpqbdyqea.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtqaceysef.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtawgvduoa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gttpprdmmp.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtpvxmypxb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtzxvxtkbc.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtpbdcohul.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtkwvrkour.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtghncuxry.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkuczfli.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtbixlxeoz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gttaoyybnd.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxpfxzeu.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgijiubm.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtrlcyriyk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtfwsvrnuf.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtoczprslp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtkhwcltpi.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtcmzlzipl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtyvliifek.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriuikefj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtruwvssvj.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gttqeucfyg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtbabjzwog.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtvmutedoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtiattdgga.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtubxvmhsg.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtkyaqjxhi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtdizdfcbh.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtavajtust.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtimbuekjg.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeyjsaki.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtsawzskqv.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtsebyebjj.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtgllcvqhn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtfemsddwi.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtubmyratu.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtfdofhutx.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtrhxagwid.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtfgdwnbwo.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtclqwziwd.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtlyhkbubx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtblzmwnry.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtvxvqntoy.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtvufqcers.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtqubsiyrl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdagjcrv.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtmkvqyvvi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhpvuspg.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtopeoarcq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtrbsglojs.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtkofcsnxj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtnkwbqerr.html


<!-- 参考信息 -->