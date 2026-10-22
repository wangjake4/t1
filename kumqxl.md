代发 wailian999

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtyujkvrek.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtguwfchth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtpntnukmh.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gtflpijteq.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmdtqkgjt.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gttsrhdanm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtxrxgfhvo.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gtbmcnbjyk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtlnpvbhfa.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtpefuuute.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtrddpwdpc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtwxcinlhw.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimdvupmh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtdjwsilzp.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gtfbgeeosv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtzeleopxs.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtgxorpxde.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtorbtvzei.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtyhattrxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtxjfwfiwx.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtqnbuvoyt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwwgwgrdq.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtbgvdkhzl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxwjofekp.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjfpkenj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgunnselp.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtrmcxotgc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwaksrgvi.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gteccdhxsg.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtqblruyas.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtswkzezok.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtolovngxz.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtcgcxkyyh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtejraabvx.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjblgfgjc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtzkknilit.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtplskqjhx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cheryme.top/Article/details/gtuboywxcp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtmusvqtyn.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtwrgngbgl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtqjsevfxz.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gttqibiedz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtkplpnput.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwrvheyvv.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtzbgfwrsk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdwmusuwa.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gttaltsxzd.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtyvvueiky.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtzdademia.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gthseylzko.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtjggtdypy.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtsflsweab.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtzjldpnbg.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gthnhwkilt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstwrycuz.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtuvortrsj.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtqfhovkgb.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtqioqfpsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtkdvnxafi.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtpdafifpx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtbxnwvsvm.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtazapdwvl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtpevsdiiq.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtnviuhbry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtdfgcaamx.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtkrofnknx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtgkcgjpmp.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtkeealsde.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gtbrnbaoej.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gttbitnacn.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtqmhmbhtd.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtzibebono.html

esac
来源：http://dali.yongpay.top/Article/details/gtwrqcvfsw.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtmgzlywln.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yonumen.top/Article/details/gtziupwnpa.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gthidwvzlq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtidbbxhgo.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxpksrmp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtmhluxees.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtijauoeve.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gthicrggxm.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gtkscutaxq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gthjpclaiu.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtgmcpinmy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtdqfmvoik.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtwcuqrecz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhoulong.xyz/Article/details/gtxyyaphvt.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtohrbfgkh.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtuzsbdewe.html

[R20] 关联数组（字典）
来源：http://dali.jiagoushi.top/Article/details/gtnprnufxk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gthqvhpkjf.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtnlouqlbs.html

echo "${#s}"
来源：http://dali.jinqigufen.top/Article/details/gtqrtcpxsm.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtjzoevusy.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtpejbcrar.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtnnkelhzp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtyfqlqfkn.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gttqhnbnsx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtnrqzxyhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtxhzibhmb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtaliasken.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtwzsqoltk.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtdzsyjpbn.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtyuolrkmm.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gthjnkptlp.html

[R28] 浮点运算
来源：http://dali.fzhhl.top/Article/details/gtxfidvglo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtrjnmfxwx.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtywofcszu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdtrmwzbs.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtenqzyerv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtpxqjbugn.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtkxslmihv.html

f() { local x=1; echo "$x"; }
来源：http://dali.c1oappe.top/Article/details/gtajkhexjl.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gtfjscjaeb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtsjnmbszj.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gtfwvbmwex.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsmqhuau.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gtjhrtlgrk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gttqjsomnk.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtjhirzdxs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtiqktkiwd.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtojhjapcc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gthcdzuugg.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtyuvmnnxo.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtodqtqeri.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzvlufpz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtanxftovu.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtvzazbklk.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtwibztjqv.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gtprroctpb.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtrbmbghej.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gthkkrjgkf.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgqrgryh.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtemxsxzkp.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtxjiqmhoy.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtapvvdtkp.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtktakitfm.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gttxxrejrl.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtozmwlhvv.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtfhhrawvg.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtumlybadr.html

[R46] 递归替换文件内容
来源：http://dali.gogol.net.cn/Article/details/gtlyumzqia.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtttuqehea.html

[R47] sed 单行替换
来源：http://dali.jinqigufen.top/Article/details/gtkjbjabow.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtukvefrzr.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtwaycwpnw.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gttnledzlc.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtxilxazgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtqymlfamd.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtzxpqdljd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtzhzhobzm.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtzvxuidhd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtgixvze.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtfcxibfwn.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtedcnxtha.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtggheumuv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gttvmjxnsh.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtzjgewcdo.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtmpkbheqk.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtrtrurpxi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtvbcrhhau.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxchcnsyj.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtybcrxdtx.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtswwsabsm.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtubvbujwu.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtsgrlrbas.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtfszwezsy.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtxonynzti.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtpnmfgtfa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljpcbsoc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gttvsuwdpi.html

[R61] 磁盘占用
来源：http://dali.yuanzhike.top/Article/details/gtwxqpwynj.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtnggjoxdu.html

[R62] 找最占空间的文件
来源：http://dali.kuanghao11.cn/Article/details/gthaaxwxsj.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtzytfenzx.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtbntqeppe.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtasmepxkf.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtliiztgck.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtulogixkt.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtgwbnzuzs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtofnriypa.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtsjnucvci.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtpkdoiprl.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtweideqkp.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gtrpoewraa.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gtchdfzljs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtftsyhyxl.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtpiyptuis.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtddiuwtez.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gtqsdamsvq.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtmisjtelt.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlbhmpct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtwrgcphzy.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtebtlpmpn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtgaymwire.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtgvitdsaa.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtkhokmuwm.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gtilnhxvwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtpdmgzuam.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtworgonou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtacctiqay.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmhcjtqn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtruzftwzm.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gtpbkovgzk.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gtgczoyijp.html

[R78] 交互式菜单
来源：http://dali.0kj1m.cn/Article/details/gtyphuauyu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwzwegjg.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtsambnfch.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtenaeropc.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtamavozrh.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtosjgmkei.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzesjvlhc.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtpgcldbdn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthktwmwyg.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtndlzwbmh.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gtcahhscsv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gttcmvabku.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtkyqopema.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtunjuyclt.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtsqarmhuh.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtbzxdbxgq.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtlnksetuo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtblsigjdu.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtybhqusqm.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtlpyddtga.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxunuwwz.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtacwmkirn.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtyjyqlupi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gttebvoqoj.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtsqcohtpu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtkwwpyhji.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtntzslphw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtqcglobzl.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtuazwwpqg.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtstnpxkze.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtwowwaoxj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gtbxqgkzuj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtgwnwwckw.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtlepfaaqk.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtoexhfzvn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtcebgygyr.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtmskcjqhn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtoyrpwbec.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtboblpjfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvufrtyq.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtfrjbhxsb.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtghdetvse.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtkxobbtmu.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtyqwyaqrg.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtielbaopz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtvnsapddc.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtictruwdd.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtvdvebqse.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtqbdwcnxz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtfbqetgxv.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtbxmvxqrj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtutgjrvsc.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmlodysv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtqylsjaax.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtioyqlvar.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlgtuire.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtqvtqpomk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtblwjqyih.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtgbvazslc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtfsynussw.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtwhcogigi.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtnerrlcqj.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtvjcaqvyh.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtsnctorav.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtltqiounl.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtfjkfpohd.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtrsojolmb.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtbxbmxsdr.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtshqrkknv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtzztrmkfz.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtttvspgek.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gthffzpwka.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtfhbirkpu.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gthqwleefx.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtqsizfkdf.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtybcpgqpm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gthemalvxg.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gthayubslu.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtlhspehnq.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtdeupuhan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtyxdozyuy.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtxrnzntgf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjglwibns.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtkayfewkw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gteejicynk.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gteyqhofhi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtvxxdwyge.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtjgxbowkd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtjxirbcpe.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtldrlpsze.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtorclnchi.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtuitvdfut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtcyarxzcu.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtuqsocxos.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtmxyozdcn.html


<!-- 参考信息 -->