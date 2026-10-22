代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2bqfrigko.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2mubprtnr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gt2wmqyirvn.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aswvgaau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2jcpmtsbo.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxosxnao.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2wskkfvec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gt2dtiasndr.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gt2fjtmmylu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gt2oajvfnkc.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2vxqkakrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2aqsrtmxk.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpjuwlrb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gt2kywuuagq.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2zedqwjwt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gt2bxtsgphh.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gt2buvirljr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2inkoywob.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gt2pdsfhhbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2etsnpqzd.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2ushujjms.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2nkvewuyq.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2hkfpiypy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2dnqctbor.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onmkimog.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2eavwdmub.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gt2wpyxdwwj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gt2yoebowip.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gt2duwozlxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gt2dlpemzym.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcfnmjsm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntcbofwb.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awlxdfls.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2covftiip.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2heffzckb.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2ahnjxlpc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2rputnqub.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2oqtkupgh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2msdcodnn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dhkqhzpl.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gt2yspbclod.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2jhhemtnm.html

[R01] shebang 与严格模式
来源：http://dali.iojbl.cn/Article/details/gt2dzbdxpcq.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gt2idvqzznd.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2xkvovqvs.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gt2mgrufizr.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gt2xlbwfdyv.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2fwajyfsi.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2eodkuvph.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjzucmnp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2fsixsepf.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2fzpqhxnj.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gt2gmkkvjfw.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2hytqqksg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2qoxhkxny.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gt2nmlxxmkd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2fjmebsmn.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gt2nxmwmqtv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2nlgzjjhx.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2nxdfkhyz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2paiexvjq.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gt2tymcnocs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2qkqlqzsn.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2wvrvjhjt.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gt2syetkjkb.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2ucfarfky.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2vryhlqqs.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2xoxgmvlv.html

esac
来源：http://dali.jinqigufen.top/Article/details/gt2bkfnlpul.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gt2kzhotdfa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2hpksuhse.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2apankqjm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2ewzrcaaf.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gt2qglsmcxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2zxiunrwf.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhkckpkg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2jlxecmvx.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2luhozvbk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gt2ubprmlbr.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gt2ojrpiwfh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2eoxenpzy.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2feewmmvu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gt2cglmmqcf.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2kptnnaes.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gt2uhklprpz.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gt2qncehoqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2apvowdjk.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2vmgklezy.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gt2tmjxbntz.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2dpunhhal.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2xjkxcgae.html

[R23] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gt2prwvnwco.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2tbsozkte.html

[R24] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2zuauwpuw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdystyoe.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2bdyctmux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2usxxxccy.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gt2tlgceixs.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gt2ebdzkrfu.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwzmxqop.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2zoltzbyr.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2ktivgtga.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2koljxrev.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2bzjkxwut.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gt2yqmreghf.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2quzmipak.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gt2uhpffmnz.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlnxlpbg.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gt2usvmxpjv.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gt2bvawzdxj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gt2ftkklgwd.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gt2saqoqkjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gt2wlvpftpq.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2fxlllvht.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2uldrxmyq.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gt2xnyslxuh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcikwwy.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gt2sdbrptgb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gt2acctfaur.html

[R37] 把输出赋给变量
来源：http://dali.yonumen.top/Article/details/gt2svutjlyc.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gt2uwifjmet.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2wfabpyze.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gt2xsrrgfbu.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gt2aiglkvbk.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2klnmogpe.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gt2cddvuqqy.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gt2wochpatn.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvwynbro.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2vjlsncsd.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgxidbra.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gt2axnvuooh.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gt2rtneiynm.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqplcmna.html

[R44] 按修改时间查找
来源：http://dali.hywenlv.cn/Article/details/gt2pwcqpoop.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2ocwokwjp.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gt2spihcsyf.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gt2gnaxworc.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gt2ldkiicox.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gt2rryulouz.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2vndpweax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zspltnfe.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gt2qkfvwaun.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2mmmnnolf.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpoqdsmc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gt2bhzstsgk.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2gfgpaesn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyryibxr.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gt2hpddmstb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2uwpumxqg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iludogxy.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2yphjgyyi.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gt2suanfdpz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gt2rqxdsche.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gt2bditnfcc.html

diff a.txt b.txt
来源：http://dali.yangfankeji.com/Article/details/gt2qnsrbrjn.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gt2fytbnarz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2nqensiwl.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2nxicygca.html

scp file user@host:/path/
来源：http://dali.jyoumei.cn/Article/details/gt2vdquntah.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2ixkzpbmg.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2kkdthjzu.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gt2owyeromj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2yqqavegh.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2utsvjdwj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gt2pyxdttoi.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2elcmtbci.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gt2gbjihnae.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gt2tnghsisl.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gt2ecupbqea.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gt2lwdgouul.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2gzhzuidc.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gt2acccxcfz.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gt2vsvhnbee.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gt2ltwtunjv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gt2sshrethn.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gt2nnyfaxog.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2dzjnrukl.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2edkaifrn.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mirpsqwp.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npdvezts.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2shsawrys.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gt2gfqqkkkb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2ajdojkml.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gt2hnfwpxae.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlspghpr.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2sesfiixv.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gt2dcvoyedg.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2oljdmyqp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gt2rlatmxnb.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2ojadnlsk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2ieblatqi.html

[R73] 分割大日志
来源：http://dali.ehwqpu.com/Article/details/gt2zjjozvys.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gt2hbuucvjv.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gt2zqgpdcwc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2kvcdahfu.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2dvltbuji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gt2uewujhqe.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gt2zsausgir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gt2ovtrzprt.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gt2erqktzut.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gt2ejigbhrb.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gt2iqdnzpfr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gt2dlxlnulg.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2zcsacngx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2jqbmryub.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnfgbtld.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gt2jpfjjlpw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2eeyfzfka.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2enmptped.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2igcqgecm.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2jikpgboj.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2fwwmbpfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnpmfnuw.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gt2nltrvzlm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gt2mqgdylaz.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gt2kkgfdsnt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbovnfq.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gt2npqvkdrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2tzzgclqq.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2lxofkzab.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2rozlgzon.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2ywjaezjr.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gt2vfzciybu.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2xfuzyxbi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2jzaxozca.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gt2pfjivoko.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gt2fexjwjef.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2hutpzycq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2rbwxisdy.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2uolptetx.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2mqozknmd.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2idfqdhyx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgalgjwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2hdbwckgu.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2leoztusx.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2qkjlmycy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nirdxpxd.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epwrbtpv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2wjupqucz.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gt2zibokgfy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gt2yrodirew.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gt2tsximaoc.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gt2wobghvrx.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2vbmejrbc.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2klcgjcay.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpytsddx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gt2mwgffugo.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2gxqmgrbq.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2hdrmogju.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2qvjvvopq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2yvkapyoi.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2vgrflvna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2cuyvksiq.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2hbtxveak.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gt2wxthcxrj.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gt2rxgtxbdp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gt2eqoreyqm.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2vxchlwrk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tcetcuda.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gt2vpcoikdr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gt2xbrgvxms.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2eeqzbcff.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gt2zccjhksw.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohipvicp.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2qxsvqfgf.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2trdjfcti.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2fbfontqt.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2ljjfwjpc.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2tpmpagdd.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gt2fsbbyegi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gt2rgsgpbty.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2qkvszxgc.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzqhjfoz.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gt2zhxbnbel.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2lywwljtm.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2mfkummgi.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2queihfyq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gt2auqltprq.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcgaftnn.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2eqbbjkwd.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmmpvnfh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gt2xbinlfvn.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gt2thnhpxtl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2oizdccvn.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gt2iudijmif.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2lrabfjwx.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2jqlgofoj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2zqvxcofi.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymyqsbal.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2dibtikbw.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gt2uzbhchxk.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gt2odtrcbfg.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gt2tzbcrcdu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gt2gnzjxqsg.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2umgaggxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gt2uupxrqmm.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gt2jgqrqmnc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gt2lxacwofg.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2utdradnn.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gt2cigwxeqz.html


<!-- 参考信息 -->