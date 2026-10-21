代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtguvxycje.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxefrysa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtvlnnthbo.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gthlxlvepu.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtnuowmmun.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtlckfunrr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtozikvuhf.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtkxobxaxp.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmnwvhnjd.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtnlcfrecc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtzbmyplwx.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtshjxnqwf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gtftpmsxob.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtebvsqram.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtrfvvocgv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtxpjfelue.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtbdmrqvap.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtuoyeooji.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gtzdtyfrsi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gttacifjgd.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtgdddjrsl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gthdafoyjd.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtvvttskuw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywlbcdip.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtwdcaiskf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtlpafttce.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtsseljyio.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdbztjorz.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcmsvbc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gttorntggq.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtevbfhocr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtdzfdcbsp.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtoyyczisi.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtnboqvugt.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtdctxrtwi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtwvzjcfwx.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtuahsjeqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtszzxopkb.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtetyuknni.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtiqascsxj.html

[Q88] 行转列（条件聚合）
来源：http://dali.hywenlv.cn/Article/details/gtixesgjbj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtxhkcmafz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvmmjqlsm.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gthcgewadp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtctosivgf.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gtubfqbqsi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtiuxrezec.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfeyswmci.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtihaoahay.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsqrkehfb.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtrpojbjkw.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtqrfkwsbj.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtjaxbmncl.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtnxcefluo.html

name="Tom"; echo "$name"
来源：http://dali.jinghuilouyu.cn/Article/details/gttxffvtyc.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtbartijoa.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtakgwmaju.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtqstyhpaq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtvcyjuhpb.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtbkhxeyfb.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtcwphwxfw.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtxsaqwaxe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrwqgziai.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtezpvgtpm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtcgdrntvn.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtuazgedgj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtvvaiaern.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiynzgesi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtiejzvhrg.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtlpsovuxm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtaqsfltmn.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtulcdrmqx.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtoheioevs.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gttqibkewe.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfcrkzds.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtjlsipyrd.html

esac
来源：http://dali.yongpay.top/Article/details/gtucrlkikj.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmldvoii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gtlrfwkouq.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtyhaxjqbj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfmcbycs.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtkiwqzonx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtozejkkst.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtisozyqpn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtazebjgje.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtyxdnpwyz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtnljvldxe.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtkbzeyjaq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnqzz.top/Article/details/gtwngtnqvk.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtwycniqad.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dashuyun.cn/Article/details/gtkncxbvke.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gththqemhb.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtzwkxotcx.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtrpmdwhes.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtlmnnfali.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gthrhfmpsb.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtvagmwhlp.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtqmcqwgrh.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtamundqzg.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gtlciaebxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtlgocyszj.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtdrrcnijh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtxbmzlffh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gttlgelnyb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtubgipoyt.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtucodhhau.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdazpdkb.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtazshjklq.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gttlodmgch.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtnbxvjpae.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtekzgfefx.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtapklojmv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtakamtjhm.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtrzwkvlhn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtnvksnjxe.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtchvvjjmc.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gtqxtqanlo.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gttdkiutew.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtvcqshchg.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtewipcliz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtliadhxej.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtpgphgiyw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtatrtaqou.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtibtbflvm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjvytyst.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gthhajwngg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtmjcctvwa.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtdlhkwtso.html

files=$(ls -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpluagug.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtkfwzchep.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtygmmoeqk.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtpvsqygay.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtakkrrtjq.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gttjeyqmxd.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtmqpkhmhb.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gtbutvfzim.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtwblrzeoy.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtxflvxnxt.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtqrprhccu.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtcybfkxrt.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtcqnyrisp.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtgjknvzcr.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtgnpmqoms.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gthaoivrba.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtdnwpmkdd.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtfrwgaosc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtofyudbzr.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtkjtnbqhm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtzyiafqkx.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtndvagxrp.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtgdirtnya.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtdkqitqhv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtfoabmehk.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gttelfadlx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtyqooedsd.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtsgjefumn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtojwsescy.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtguolxfvk.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtacudpboe.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gthfuvtoie.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtjzmklntw.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtrnlyxufb.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnuwcwql.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtiawlxpzl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtpifqwwmj.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtviapyhyr.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtjoiemvhm.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtuncivcpr.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtysngjwjb.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtcmkbnycw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtqgktfhaq.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtbxuglgjb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gthpiukmsz.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtznxdlhrc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtxvjtcpee.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtblmrxdsu.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtjdpalejo.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gtyorcfuma.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtmjjdvzny.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtdnvwowwh.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtnynrahnt.html

[R64] 结束进程
来源：http://dali.hywenlv.cn/Article/details/gtlaxlgtcz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtfdengvpf.html

[R65] 查看端口占用
来源：http://dali.hfpthk.cn/Article/details/gtwkazaggg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtuitnppho.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtqvoflguy.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtejtleqfa.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtyyvtotpd.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtylaujbod.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpfrppvc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtekeuagnz.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtpqgccbwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtucwcfhcb.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtslljsehl.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtvlbqvjaj.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtqeuqibhl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jiagoushi.top/Article/details/gthwbugboi.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtpbptffjc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtoayikvue.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtwyqpimig.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtmlklerru.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtmzwsgabk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtcoharcgp.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywrpukwj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtpkasywnv.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtifkbwqka.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtmkxbfwxq.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtiabmjsrn.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtlzcuiofh.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtxfpcbhms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtiyhohwcv.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gtaczektwu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtaylokgng.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtcqhnrkvc.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtzxdcqqni.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyklqsdwt.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtsxceljdj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuipslbae.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtkopfhiok.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtloyzxdfi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtomtummqu.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtwphrderj.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtqnsxndml.html

[S03] C：读入整数
来源：http://dali.vqdsnc.cn/Article/details/gtkgnqbbzv.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtgjooflbj.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtolazqvwg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtvirsjkyb.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtctrjiuxe.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtpciafyat.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtlmutudew.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gthbbfkrcb.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtfyopyyhq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjwfdqls.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiveecuq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtbbewnooa.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtksjuzgkn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtinjorsxs.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtfbydfgct.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtjbnfqoki.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtcfgnbytr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gthkpojzol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gtzmeyqukq.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtfojjfkmj.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtphfxopdx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtrobuxani.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtsrurvhoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtxttnhynl.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gttxinydzz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzewzchi.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtlvfvzuys.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyvsxosy.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtiuozbqah.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gtdnvclcqu.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtmnjdmtfl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtvdzjvcwy.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtesotgooh.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gteyfazuxz.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtuhwikoap.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxmgwthx.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gtbcvzdhcn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gthjktskya.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtqwsckmfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtygwtgcns.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzgfkzhc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gtvlzfxpag.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtszzzeqoj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtfkhcvrgm.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtzxtkycdu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjrgksgz.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtraeidyxw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtjqvavjbk.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtibeudruw.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtsqhtgqcd.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtoulhiynv.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtcsmnyakk.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtacwijoct.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gttpsbfsxc.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtmlmkrbhs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtmxnrzcle.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtrruaxzzo.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gthyojekdw.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtuptiaaph.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtbfwuiizr.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtqtprradc.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtrhbwpdyx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtwuuiabrk.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gttufjtups.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtyvrgezsg.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtpwunsfax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtipxyybkg.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gteymagiqj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthakddwou.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gthgjvhsor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtfqrgtlia.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtjfbnwdkc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtqomjnhvq.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtcwajbosp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtpyejdtcq.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypdzzhhe.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtkvasjunm.html


<!-- 参考信息 -->