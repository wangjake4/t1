代发 wailian999

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtxsglqypc.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtojweijug.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtvhvrfwwq.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtksarfgek.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtcnrrmzee.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtbtsoavvp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtzqlztyko.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtcujxanwy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtfadrgrvl.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoatkkmc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrydtsecb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gtauympywo.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gthexrovde.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gtjdttaasl.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtdzfdekcv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtawkdviou.html

[Q78] 当前时间
来源：http://dali.cdnleiting.top/Article/details/gtzugrfcof.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtfvtctbcy.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzwfbukw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtdkveplwj.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gtjvppmvdz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gttizrarvv.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtnccijgav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbpgddwsf.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gtsetodgmv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrfludcak.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtuljqchpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtxrktctub.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtupljinhq.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtvfooxtxx.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gttujeixnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gtbxgrrcnl.html

[Q86] 读取 JSON 字段
来源：http://dali.xuanzx.com/Article/details/gtbplaqkkv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtgvldlhbq.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtxjdtijmm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtugmvygrb.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtcsrvcqgu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtcmbfjtzk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gttaekgwuw.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gteqcuonsd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtniadjusp.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtfdpzmujd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gthbmiymxb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpzqpyrof.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtxndsxxlk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtubbscrud.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtvatjddly.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtinwhkzor.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtcgrwymtt.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtryqpqqim.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtbaklqyhw.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtlrylinaz.html

readonly PI=3.14
来源：http://dali.jlsjyb.cn/Article/details/gthdvztlkq.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtcfoseqwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtxdvqxykg.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtqlaqdmjj.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtclloyhlu.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtvuimemmz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtupvxutpw.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtahowhinw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtysxghcth.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gthoxofxjj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtagnzzdls.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtnvftqbju.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtjgduucoi.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtzgbhpmgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtsljmfssj.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtkecvyntw.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gthqfvtjrd.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtilcpmgej.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtiammhjyf.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtyueritko.html

esac
来源：http://dali.316326.xyz/Article/details/gtnzioizlr.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtklvzxpws.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtgeygeufm.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtzboyjzyc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gteelxrjgq.html

[R14] C 风格 for
来源：http://dali.feifeiyinyue.top/Article/details/gtjmrdagpd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtcsgkyztl.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gtnxfudljz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtxkgiyovk.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtzekfghiu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtsoiuemfn.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gtasltgvdl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtpjpwbxfw.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtxsrfadoj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtxzzjxxdy.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtxznnxuip.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtfflhwreg.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gtgdzzvgbv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtbkwuxuld.html

[R21] 字符串长度
来源：http://dali.cucudq.cn/Article/details/gthcgbyaps.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtepkaasrg.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtrsxwlyhn.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtapnnmcbi.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtgnpwbotj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtqezdbdce.html

[R24] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtheyvesyv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtkciajxhi.html

[R25] 去后缀 / 去前缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzbewtgl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtkyfpbzem.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtqxfbamkr.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gthahivnhh.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtcgoxefur.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtdfivexoa.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gteksytlwc.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtlayozila.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtdlemlzyk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtpkzyqpwo.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtsjonqrzk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtofswmrop.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gthwhnqlxd.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtjhjskhsu.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtnxwxnicz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtatrqrxxk.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtnrtnnrma.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gthumgxtwf.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gtosoehqra.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtfejvxazg.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtmolgkmjb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtsstzvevk.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gteffnxaci.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtruoifuae.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtlfpwygqx.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtroojwhzm.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtwqfkoooj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalawvumd.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtpuhkaion.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtlqbczkwy.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtlkflatcg.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtqwoocxrs.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gtlrvopyvf.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtllyoscdt.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtxiqnbyts.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtnemdsflb.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtptuxfmud.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtzaznmdva.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtnkmkhmtb.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gteintbnap.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtxepqvmis.html

find . -name "*.tmp" -delete
来源：http://dali.wangshuangyany.cn/Article/details/gttztlxtzm.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtfdpzqlsx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtjivtruan.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtensliewy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtknvgzfoo.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtzlyaxsmk.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtdpndftid.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtsazutupd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtqdkglwkg.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtskpczyej.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtdvmaouyr.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtkwqszdph.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gttokzjjby.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtrgjnjqeo.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gtqxmxscgv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gtvycrfkqk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtqoiftiic.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtvvhhkzgi.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtknvlaoqp.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtoqwghzwb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtjbvohmaw.html

[R56] 远程拷贝
来源：http://dali.9152youxi.cn/Article/details/gteiofhqlo.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtzjfevrzh.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtxevxxvyi.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gthhpskxxh.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtkyjfnsuk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtnocycofs.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtyswgtull.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtdiyzkcvb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtclamarow.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gtprkfieqw.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtylhpooke.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtblnommpn.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtumepjqli.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtkbuygwyj.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtzojjcyyv.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gteykzegxj.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmbqnrib.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtggfrhrbt.html

[R65] 查看端口占用
来源：http://dali.xinyue.icu/Article/details/gtwqrsawte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtrvingasf.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzleszfer.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtgvtkfavd.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtrckfnwbj.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gtdczmynaa.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtusolpbzo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtgcesdkeo.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtsfetqjvm.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gtkwoqcbsf.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gtiydupddk.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtknvwabfl.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtpesrsqmg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmymefapz.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtebyexqxi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtoqnacnut.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtldxzsqcv.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruntwonz.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gttqaixowp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gtcpgbgrkk.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtoexuwpuo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gttexlfcws.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtrninjzqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtnokbtnth.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtowabgper.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtafmlhewi.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtcrirvobq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtwszxjqlv.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gtmhncdtpd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtzsnetuyn.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtcaicyras.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtgbwvuzte.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpmzyflhx.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtiaabupxp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtighmsfqo.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtwrzjqnlu.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtdctekvbv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtmgyqnesw.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gttpykykxu.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtrtkbypug.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtkrrqibkh.html

int x; scanf("%d", &x);
来源：http://dali.jyoumei.cn/Article/details/gtucmmyyym.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtuidbspuv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtihhnlqti.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtsqorsjvm.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtiahwezln.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtqntqdhts.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtemeqsxbu.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtnfsxnspm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gteswobnrh.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gteqccboxk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sufxvd.cn/Article/details/gtnttbmbvl.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtrdvcxrqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gtmvompdca.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtkrakvltd.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtftbypcsc.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtmyldebtd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtshjsrzmf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtqolaviap.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gthmbybuhs.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtzbqajrjl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtvbbsumdj.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtkhpecjbe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtilqfhirs.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtxihzudsd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gteyimukch.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtiysqwyei.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjturnss.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtlphvdznj.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gtegldkezl.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtcupzbzjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtuafmjndp.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtljuhlkwo.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtuixrtsuk.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtijcsmrlr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gttvwzzvjs.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtyntkaiig.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtlmwflrto.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtjchovslj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtqlsupaqz.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtnydlqcnj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtphtpnetq.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtotkcfuyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtvqajgpuo.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtqaxhpggx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gtqivkpvim.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzmvbopd.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtvfheooam.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtrckdtorp.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtmortleyl.html

[S27] C：定义常量
来源：http://dali.jinqigufen.top/Article/details/gtbqfxwmyy.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtldzaovaq.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtldchyuqn.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtlkpwymjg.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtsdosfzrv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtkbczvjbr.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtskwdehvj.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtdoejfjyv.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnghbqwh.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtskotyhpz.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtgwaklxrq.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtafomrabm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtofbqenav.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtlqyvmnke.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtbxgnnlga.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtgxctdlow.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtvgjakbox.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gterpqlimf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqgkfho.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtnkwacgqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtcyrwcigb.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtvthlqqzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtvahmbkeb.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtglejbwvc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtpbqiylur.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtlmksrjja.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtelsedcfv.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtdmojonxa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtbgcsvdgy.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhjzybsa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtiwwxufct.html


<!-- 参考信息 -->