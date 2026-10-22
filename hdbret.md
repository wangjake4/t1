代发 wailian999

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2gmklnvsy.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2nisjmpxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2aluvydmh.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gt2gotnfqcq.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gt2wibesldy.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gt2ppgojuut.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2sbwikzhj.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gt2pyiggtva.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gt2suowpwef.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gt2jnuskknh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2uvnhmwwp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2ccojcrvp.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gt2xmjabmyo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2wwllaesp.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gt2gvkyqdlf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2rojfrtnl.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2vshzgyty.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2briduciy.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2ktlggrrf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgsbdgxk.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2atfwjbzg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2fjzrcwem.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2vetbyuhj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2adtdoiiv.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2uvgkzyzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2mcvuyozy.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gt2majsajoj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2flwxirbv.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gt2inxiuqka.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2spimqznk.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gt2qxjogfov.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gt2cnchkfdr.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2xjhozqgh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2xryyioev.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2mkhlbqzd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gt2glslrdek.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2dtsrewdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2unxcburi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2umpiojym.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gt2sjsyieab.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gt2mreocytm.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gt2phioueii.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gt2pdjbrces.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rlcxtton.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2tbkfuvmx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wlwtvfbe.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gt2qxubrvon.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gt2vtfqdjaj.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2qxnbnatg.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2wtoqbbdm.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gt2hzmtmlom.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gt2awpsugzt.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gt2tujoulht.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gt2engmquef.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gt2dkqxcsjh.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltohclii.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gt2ogmambnt.html

[R06] 判断命令是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2vczpfjgc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2mkdvqwya.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gt2rwfnzmrx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2ivpagujp.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2xouuvayv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gt2extcljtx.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2nleqvlzt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shzxlz.cn/Article/details/gt2jahwqyzo.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2otkjvplx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2ytxfcbwz.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2dsidzdbx.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2mjedzzrs.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gt2kcxqbaks.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2wushpjyw.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2rkftvaqe.html

esac
来源：http://dali.nanxinkj.top/Article/details/gt2sdwseser.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gt2vemxonxn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2vserdwrv.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gt2oqwosrny.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2fpnwhjak.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2jntirfby.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2rwkfieee.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2ukmifcqf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gt2zsvymclp.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2lxppwryx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gt2hxutvzvs.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2ewcdflqy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gt2taiixqpj.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2zyqxybjg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gt2oskuyzhs.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2htbttksx.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2pvghkbou.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gt2wshladbi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2xpqcrnzj.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2arjbyjtj.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gt2sztuglns.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2luzotqsn.html

echo "${s:0:5}"
来源：http://dali.tian-w.cn/Article/details/gt2gwhmezop.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnqofblp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2gouooyys.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2lsabskdz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igrkwldf.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gt2foyzndrr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikvybqmd.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2jdccymgx.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2fudvnkhr.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gt2kommwkxn.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2osrrjnhs.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcrsnopu.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gt2vfavredt.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2bjryevic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2goxzmezh.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gt2ierjqlvk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2axgafwdr.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gt2rhnmwgtx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2xjnohvoy.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2hjlccsly.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2rkzbntgf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkbzckd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epucueme.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2qporozbw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gt2wzsjesmf.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2itdatdmp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gt2qgzrntgi.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gt2ttrlxbya.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2silnqfwe.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2pbcopvod.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2yivrsedy.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2jqeirnzi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2ghcmjdhd.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmglpukr.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2tjifstsf.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gt2qpuxnwuc.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2diinkllu.html

[R41] 丢弃输出
来源：http://dali.c1oappe.top/Article/details/gt2fdsstuqx.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gt2wvxovtra.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2qgvqcfuw.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2qmmcbixi.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2lfdpvjwv.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gt2qqddtkdi.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwliobfv.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2ilkcnudu.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzpcidlx.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gt2tfnkshmq.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gt2mssbbkml.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gt2nubnxysi.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2rakzltgk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2mfmgbbkr.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2eqyktlqa.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2uobfzdxv.html

[R49] awk 带条件
来源：http://dali.cheryme.top/Article/details/gt2iwgpdghp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2vtepfpyi.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsgeivyb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2fetsjtgu.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2mbllanqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gt2ammyacxx.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bydvaeiv.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gt2ckpeoqtc.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2wrcszzed.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gt2jdvunmgu.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2fjyxmerg.html

diff a.txt b.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdipgkpn.html

[R55] 压缩与解压
来源：http://dali.316326.xyz/Article/details/gt2gvntjtvd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2gmfugllt.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gt2xglwwfrq.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gt2dxjuvnsu.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gt2naphdqvo.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gt2jpqwahav.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2uvlcvaap.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2ucigikyl.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gt2rpgookbm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2nivbrzlz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmzvifve.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2sieoicsg.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2vckxgiwi.html

df -h;  du -sh *
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpgygzjg.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2crsherzz.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gt2hdjhmhtz.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2enscrkqu.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2lgkflzvt.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gt2xnmprcsh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2vpnyosrt.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2znwvwgam.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhoulong.xyz/Article/details/gt2gxpkcvrg.html

[R66] 定时任务
来源：http://dali.havefunace.top/Article/details/gt2cnidicba.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gt2whzkdtel.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gt2igugscmg.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gt2dzthpsuo.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gt2wvbplrvp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2zamxwdhb.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gt2sfeqjgdq.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2cwuntana.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gt2jzykwhvm.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gt2hezrykvn.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2qmcrjhkn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2seoxzjxu.html

[R72] 等待端口就绪
来源：http://dali.snrcjt.cn/Article/details/gt2hegrttvb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2ekpdvmkj.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gt2dzjlxinu.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2cbjndegi.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhlohvco.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2shdrrqfc.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2tcahwpft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wshrytbi.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gt2dgcpvcgd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2tpalpqvr.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2csfrdhyf.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2efsaokns.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2drkucgvg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gt2dtvsusbs.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gt2ymjpfdrg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gt2zduqvqja.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gt2mwyjgoad.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gt2duqkuyuo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvxwqted.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2lnahrlzk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2yvufjjmd.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2hckskyyi.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gt2boohbhjd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2buwqvtfw.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gt2ziwyxukh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gt2mqeqygxo.html

[S03] C：读入整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mojcrwfy.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gt2msombgwg.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvdftuao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gt2kamtsibk.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsxxljql.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qerybabk.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2xmcfubld.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2thuytpus.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2mjwzkxle.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gt2jhpqddvo.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gt2sinnebpu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gt2iaeumjiv.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gt2kjvcovtb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2twwzscre.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gt2xqocufpc.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gt2sftockyb.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2bjiupwqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2mbuapvvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gt2yjvwgysk.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2acanbrxh.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2pdipdwjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2htozfsur.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2vdxndxem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2oyyjskrv.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imoijttf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gt2iikilihs.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gt2cplklyqu.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2ebnogflo.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2ribabgjl.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2veiqemhh.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2cueqjyps.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gt2okynhkin.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2dqgzubyx.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gt2lsmrvyza.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gt2gxxedgfo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2miqxulut.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2zmtjprdb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2arabkzxq.html

[S21] C：字符类别判断
来源：http://dali.shzxlz.cn/Article/details/gt2wtvkykvb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gt2hzuhfezv.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gt2bfsbxpsl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2battphfp.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtgvmerj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2gsnhvzhd.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gt2zkpdgvlx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcmwqmpt.html

[S25] C：内存拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2hpcfmswv.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gt2rcbxcgpe.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gt2fnvdyyhm.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gt2pfyhiebx.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gt2xdgupjyr.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2grhjeilq.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcyjcocu.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkksjphu.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2mnwcafhx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gt2iuheltpl.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gt2giickbuo.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gt2apnmqlwn.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2vdoepvip.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2vuqftiop.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2iaxctzte.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gt2fasqaioj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gt2vhjgwwkp.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2ohshschs.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gt2tojccweg.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gt2ghinwtmo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gt2xdscjyoo.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2bjabhbwe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2jqipadfa.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2ytdnqdpu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ndzruuxu.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2injlaxlh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pggxnqov.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gt2lurrpdkh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhfwncbq.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2zostrwzg.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2yflgovmm.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gt2bqesojce.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2aylujgks.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gt2jjxocjdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2giucnrbk.html


<!-- 参考信息 -->