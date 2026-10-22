代发 wailian999

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtdtfusqio.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtskbikups.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtsntptfjh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shuidangran.top/Article/details/gtumumetvw.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtywfbnujc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gthdbbbwjn.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtbizmupsb.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtkewfbkwt.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtjsjminbw.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtvykumdjo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtemhuzuit.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtxkxvgjue.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtdwixsfry.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtyqoeepwd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtqavmlmoq.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtwvckcrjy.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkzclumob.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtuxteuyjt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtltpgscgi.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtkznqiayv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtidcrbfqx.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtzmmmgivy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtuyvxnphr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyncukxen.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtleqewexh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtshbpraro.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gthwwhqrtl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtlwgrmnvq.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtjnlddqra.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtxsgbnkhx.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtzagwwmuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtmbrerrzk.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtxrfcuohf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzuhwlgml.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtsppmxpnv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtainvffvr.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtkfmwongq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgpqzyfwg.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtajpxgodd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtbakhjyzh.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtalrxhlwb.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqzgktbfo.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtepbxtiud.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtufsfhlsl.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtxetjfbbb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtpejnhwhh.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtsnjcmibe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gttwfeegma.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtxqufjzoc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtofnehida.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzczftbnk.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gthbklhygm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtylkgqeyp.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtmcdvlarz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtcblurzqp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuugisffi.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtbucomsbj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtibbachdm.html

[R01] shebang 与严格模式
来源：http://dali.yongpay.top/Article/details/gtuaxgszfc.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtrgkstaea.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtvlrnldmi.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtgsetdsmv.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtjlkwtxod.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtdknugbbt.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtdpabtxkk.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gtxlwjmjdp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtlmygkvqn.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtjveedfcn.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtqefdrsuo.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaijfhbyh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgqececec.html

[R07] if 判断文件
来源：http://dali.andypj.xyz/Article/details/gtszhpoywg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gthmyxfvcc.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtbnbjujuz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtoabylckd.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtgqrultzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtudvlsskm.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gthujamrki.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtnbyoolti.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gttukdwxzn.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtivtmdkql.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtobpyzsyw.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gtsokiywxe.html

*)     echo "未知命令" ;;
来源：http://dali.0kj1m.cn/Article/details/gtvctsnuxx.html

esac
来源：http://dali.fengsongda.top/Article/details/gtewdrxaex.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtimarcaml.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtcoamqeay.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtdfneubui.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gteivwefyf.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtcjpyhdez.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtvuesibqz.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtxcxbjtfo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gtqemxcpjl.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtmwfwsbcl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtorpkwotj.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtqcuerewv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtjztbrwyc.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtfooagmav.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtsnsfalub.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtdawwxzsc.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gthmcuszkx.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtbxuhyton.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gttvjdkphj.html

[R21] 字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gttfblzgsl.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtvwwpsoxb.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gtbexkwixx.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtgqbaqwjo.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gthreppmca.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtouyyqaek.html

[R24] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtrywrrqae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtlhpwtsyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtxvbsuuvc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtkrigiymn.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtfpgvrwto.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gtfenzttyc.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtmapmulbj.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtnfsckibl.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtdpkpjemr.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtqvepyfvc.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtplksmfys.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtpdmheplp.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtkioieaol.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtsslrxsmw.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtlivfgflk.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtgfplxyan.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtpwfjzmcl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmshhcnw.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtsquonksa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtsavxskyq.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtabwjbgnw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtdweltooo.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtazilgrpl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtysbqsypi.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtutlnkvjm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtnmsobqaw.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gtrfwhvvwc.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gtrqxaiegp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtjklhndge.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtuldzdumw.html

[R39] 重定向标准输出与错误
来源：http://dali.nanxuanxn.top/Article/details/gtcugypicf.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtypyrsaag.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gttrjdpqsf.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtvrokhltd.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjszjhndb.html

cmd >/dev/null 2>&1
来源：http://dali.bjfxy.top/Article/details/gtamvdsepz.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtqltaqcgf.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtqwmssodf.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtcojdgxkf.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtsfcqgtfe.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbabpqmn.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtgycwcrjy.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gtmakckows.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtmaljpoby.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtwgpnfnbv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtvoodjpyp.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtwigmfqbs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtwlcptoxw.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqvcjisw.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gttgophsku.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtjakeeqyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtghawywuu.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtrlmcrbwd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtafuflnfl.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gttkjjsgnv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gttghijedi.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtqafnfkwj.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtgzzeocba.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtgppdaduw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gtlmafntmh.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnbswgfos.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtwobvndrn.html

[R55] 压缩与解压
来源：http://dali.tianlin.xyz/Article/details/gtkvhowjne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtcilmuxyy.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtphbhuloj.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gthwosbqox.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflulckfg.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gtaaynbeoj.html

[R58] 下载文件
来源：http://dali.daria6918.cn/Article/details/gtgrsnmljy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtnrgzqqpt.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtphullkjv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtvnykszbb.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtxscadnca.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtodzaxwoe.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtssosrezm.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtsgkbxhxm.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtsnqfitwf.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtcmyoxctc.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gttbkgyair.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtdyndabqe.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgwizqdj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ivvv.top/Article/details/gtbazrburf.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gttfdsseaa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtihiiujdz.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtwsfncrhm.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtbevjlanj.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtebvfydmk.html

openssl rand -hex 16
来源：http://dali.nanxuanxn.top/Article/details/gtezigfobe.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtlmrslsdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtppdfpwjp.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtdyemqdmh.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gttyfbvawj.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtbrhqsxzi.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtbrjjlnio.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtalufazmw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gttsysgfve.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheuefhsl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtdsygvecy.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gtbwvmiskv.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtokeaccdh.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtocyvpaag.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtqnafpsya.html

[R75] 导出环境变量
来源：http://dali.zdqjudy.top/Article/details/gtkaxfxexb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gthdqspipn.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtnjxxizuv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtahqisiio.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtjzoixxqo.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gtrsyizdxc.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtguefqthr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtrkuwjltu.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtejokvbmh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtkranujej.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtdnpybiqu.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtezkcujjx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtumsbhorz.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtogxdtriw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtumonnssn.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gtenqieuhz.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gtcbapumio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtchqvemqz.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtmnyasdvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtivqcyajd.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtyerrtanb.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtcltnampf.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtrmcvqyqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gtlznbpwpq.html

[S05] C：字符串长度
来源：http://dali.tanke756.top/Article/details/gtabgrazrl.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsogwhjwv.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtkvidufcs.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtfyoiidjy.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvqolrrc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtumgyceyz.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtpvlmzsnk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtgkzicqeb.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtuikshnsr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gthpzlogev.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtewuotdxd.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtdouktahf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtleeoopvo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtnnaqsczo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtpmhoelld.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtbrtinnbq.html

[S12] C：写文件
来源：http://dali.fengsongda.top/Article/details/gttnggsfyr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtlkclfbsz.html

[S13] C：宏定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzjmcsxp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gttiaqnxwt.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtiktuogys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtvlfulomn.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtbllwtgeq.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gthntzlujl.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtlepupvkf.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtvmsjduwp.html

[S17] C：安全拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvxdewqzz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtswiidmrw.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtcjvcuqqe.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtgdamahwt.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtdmijskfy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtobqgvfxb.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtsqmskqtk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gttbrnnkja.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtjfvxnvek.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtzmeqnwxb.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtujdiqokc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtwnohaoxk.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtfrwewszi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtvzhaxvmh.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtlpamjryc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtbidoijiw.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmmbejm.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtwohvqlyx.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtunodgzcr.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gthknxqbrl.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtpblahadh.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtzhrbuozw.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtbhqhmcey.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtckxdcjvz.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gthcrgxwpy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjtfbwp.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtmqlimfby.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlbtetzc.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtlgncarut.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtqgpbkymz.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtdowqgimz.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtdgwzucwy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtfahgnscx.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtpwbcqqxf.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtovmpatlv.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtkkwalmcf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtmkixvulv.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtsmvysxnc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtvlsfpepi.html


<!-- 参考信息 -->