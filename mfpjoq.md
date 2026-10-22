代发 wailian999

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtbgsjhtme.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtwggznpiw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtnjujpwok.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtoaxjnise.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmpiqvlt.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gtburgvnyn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtlxucjfie.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gttuzmwadu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gttapipper.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gttgwthsxt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtxlsnbqyn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtkjaidtkj.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtppfdqils.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbbnynsk.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtlytjyxhz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtjkgrrpyi.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtprlddwoz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtvijvnlfo.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtxzxusruh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtmafxwyvy.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtfqhpdmpz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtzhhioiey.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuewfucbx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtiunfzgyy.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfnmfqag.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgycmpwgp.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfymrhpa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwgzmweyc.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtvigdxuer.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtoygvozkj.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtrhvannyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtlvrnhjei.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtkqitvegn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtnznjzjho.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gttbwjxcqt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdroslusl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtrrmeatva.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukujjbpo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtxautrsue.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtqnmqdjtl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtmfewzfwb.html

[Q90] 生成序号列
来源：http://dali.hammf.cn/Article/details/gtqoxnpilf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtseiydwys.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxwudgmu.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtxqacyhno.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfmlggnxs.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtmdhlywmx.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtxdehbnca.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtalkuzceg.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtevbafjkn.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtaloldvuf.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gtcgzmenvi.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gteghrrxoy.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtcbassdzt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gttbsmxfik.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtzklgebev.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtwunnvgaw.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtepqgncyi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtevpirlpi.html

[R07] if 判断文件
来源：http://dali.nanxinkj.top/Article/details/gtncghizef.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtnqjblhmo.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtlqhweqtk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtdapvbxmv.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtauydziap.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtladgdwmp.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtywnvulqo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtruhftbhx.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtulzjlwyj.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtqtnjijvg.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gthjfwopzv.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtzqwjagug.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtcuzxwqyl.html

esac
来源：http://dali.yvedp.cn/Article/details/gtdmukfglo.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjnddmoh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtgjlvgiwo.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtdbzigfph.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtsgpgpgzz.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtjtqawktz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtkehvhkgp.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtjxdhozye.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvvsfnif.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtmcpjzhdj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtzkdhyajx.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtoptjngik.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtdtgxuhov.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtfwosbzlc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gteewqywru.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtspmfuwtw.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gthqfhctfp.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtuvmwphje.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gtbvubtmzw.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtgdlpvanx.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtswmujyuq.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtkgobyrtg.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtdnhhodam.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtwxmxcagb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtnqwnowcg.html

[R24] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtwiphdygr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtzwgcjtoa.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtcxyzucqp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gtksxvchuw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtdkqiqgjl.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gtesambblb.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtjuturlwn.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtxdlqmvnu.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtlecjohjm.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtdecahvnt.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtsiekivcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtrvgvxfvq.html

[R30] 函数返回状态码
来源：http://dali.cashguo.top/Article/details/gtwvxthjof.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtjdavkmrk.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtsegjszvo.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtjsogyfjz.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdjaetnm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtdwhxmtzz.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gthlvspdba.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gthnltiphn.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtmqkvjtty.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtrevrjnzc.html

[R35] 后台执行并等待
来源：http://dali.havefunace.top/Article/details/gtyxuvdkxt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtacpxwckh.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtzsrsvvfv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gteqkkgafn.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtmfrvzusl.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtbvighnrk.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtwwxbjqqe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtpxelktpx.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyrtarwj.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtwhqlcqte.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gtzpgmtpdm.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqngdgxb.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtbgqqslrt.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasadwjcu.html

[R42] 输入重定向
来源：http://dali.yj20258888.top/Article/details/gtulxouqkp.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtpdguhpyg.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtdkudomdt.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtrprwpdnr.html

[R44] 按修改时间查找
来源：http://dali.chenjidiqi.icu/Article/details/gtjgijzgqe.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtlbdzwjgr.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtnujbqfrl.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtgamziksy.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gthxdiskgm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtgidpyjvo.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtkjmmrevc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmxbdpjdd.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtzmrrsgxl.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrmycrmg.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtysraomvj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xinyue.icu/Article/details/gtrpykkfwu.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtxyxvtimy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gthyajzyfw.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtabzddvjv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtnwjuppvi.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtkoxvctkd.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gthlpcyhmq.html

[R53] 查看文件头与实时尾
来源：http://dali.hfpthk.cn/Article/details/gtevaerzbq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtgprtbkgs.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gttpxysfka.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtivokdvys.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljfjkvnl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gtelgydipk.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gtzdhdvuro.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiujbxjku.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtjdeoygsf.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtmpwwjwwb.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtweduhrlj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtqgjhviek.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtcbebmgwq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gttpowsofk.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtdztufmdk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtyxxznnef.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtelcqhouq.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtpjzjnukf.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtrfbpabxj.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtzzlzepar.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtgobeywro.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtrkydlxqx.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtcsrnrsyc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtggrwejcs.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtpzmvnqkd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtvmkfkmwf.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtalzlliht.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtrxwxgsgb.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtlyvnzfof.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtowemsnyt.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtqlknoknt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gturjifvsx.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtdfgdrycw.html

head -c 16 /dev/urandom | base64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpqrypnt.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtuwpzrkgr.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmurwwbsd.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtpzuftroe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtdrvnvmlw.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtoodixiub.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtojupvuur.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtixgoaoek.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtxvlbrrfi.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmzsrbjc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtgjtbsmdz.html

[R75] 导出环境变量
来源：http://dali.yuanzhike.top/Article/details/gtkfugszwb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtgifndinu.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gtucnmsxfb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gtgqvcbgds.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykjlbyxi.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtxckljmwl.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtnaaezffq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtbvefvhvw.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtududruua.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gtqjkvfurz.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtgecygbvc.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqacjqbxt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrvslxjus.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtaqbdmyqk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtntazdeqz.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtvshaihxp.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtewbmrmbz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtstxqtbwd.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloegjtlq.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgzjxkrc.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtytomqorj.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gttmvcpxpk.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtsxxrdjhc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtkxyekpyp.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtnoohizzq.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdqvxqabe.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtkzguijjj.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtqknalypk.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeairtme.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtugchtyeq.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtneyrmoac.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtxjjvyuar.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gttmfuplvj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtdwobxyac.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtbgmueedc.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtzoahsuxf.html

[S11] C：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtbblzsvyw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtppapomsm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtbndnhhyw.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtsezewrqt.html

[S12] C：写文件
来源：http://dali.daxiang520.top/Article/details/gtwamslwjw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtbzmojkzw.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtjblcnocl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtxfaqarhw.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtywgsdjaq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtslgfudti.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtbapdkvmk.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gttuarsmzb.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtwwaeqtst.html

x |= (1 << 3);
来源：http://dali.shuidangran.top/Article/details/gtafmymupx.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtnxjhggth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtxplynfzs.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtocoveawa.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtfyglhznn.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gthkuqgnkr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtszhflokg.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxtfutyt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtwyifpnci.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gtwxrtpxjj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtssppetmx.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtusklfdvf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtxtskqlyx.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtcmqmyhei.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtpgozkios.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtrtsvzaob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtptcpoabv.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtsmqzgtth.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtswaehhxe.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtbbcpelfy.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtierstcov.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtnohummqe.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtvtjbicfv.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtyfxpacyp.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gttnnijwal.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmxmwdlqj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtksnzgiyg.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtxpbnhyeg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtljvpxgbm.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtsgqdimhc.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtaaaadzdv.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtixezjwbp.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtydnkjevo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtudkptdvz.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gttfblekeh.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtbdmelxhd.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtzokokwpu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtjlmeuusn.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtfohmarie.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gttdrqgrik.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtedatmirj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtlzctlukc.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtykhdcsbo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtihsesxdg.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtfxyuwkct.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtocowuigu.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtgjxezfvi.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtuxzdnybq.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtxkldxqpg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtblmtjghl.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtekyaziii.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtgmstnlnn.html


<!-- 参考信息 -->