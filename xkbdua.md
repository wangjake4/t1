代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtgkwpfbyi.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtttqfbohz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtadwstydx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtguxxhbii.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gteepnpkqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gttkovypor.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtnalldvoi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtwxrkdobi.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtnzjhwfra.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtowjmruol.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtfvdxxhch.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gttznhfbff.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtzmifykpg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gttzvzakjp.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtbatqdoif.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriuqdyfg.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtzxscciyg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwzewwqkr.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtvdkyfpqf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtjyrhnseb.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtcpfcoptg.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxxjmcfye.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gttfkmpzwy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtvjvmcwbc.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtiozrmalt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtnrynrhaj.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtonepvzqj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtoalqfrns.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gthxfqdfpc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gtakuuvirv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdkctaoqp.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtjdmwbslr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtwhutpzmu.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtcmnlmyrh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gtcmdupuns.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlqskrhjz.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gthcfgzbcg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsuymveqb.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtpvdlgzyv.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtpwpkpcer.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gtzfxtspee.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtdmpwthtq.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtjyijvnqr.html

[R03] 只读变量
来源：http://dali.ehwqpu.com/Article/details/gtlrvavezl.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gthvxmepxm.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtwadxrwyj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtdsjpghdw.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtmijgtgdk.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtdcskzwpo.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtujymrwgj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtllcpwfdc.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtianfftih.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtahnxjzbq.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtfixyvytq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtrijarjzw.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtswdhwong.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtvfbhhbob.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtdreudldk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtkaxxmczm.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtaglhaxwb.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gtauhlcasf.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtbybgiehl.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtrqobmzwm.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjbmqyo.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtryoakwfj.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtenpeteid.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gthpjrcwfe.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtohlfkmba.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtmohjedde.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtoxjyvubw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtmhgbxwsb.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtuqminpec.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtswmluepw.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtkzybsryj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtcgjytnxb.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtpmglbbke.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtzloayham.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtluvqnrnf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtgkguyyzz.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtwokmwvzv.html

echo "${#arr[@]}"
来源：http://dali.sufxvd.cn/Article/details/gtnmhzogrm.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtxyzkhtjv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtxreazioy.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gtmkchwyja.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtnxctnufi.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gteqnqhtbv.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtprbhgimn.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtlnwccsgk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gtvhihbdlo.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtcoepnrwr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtgaolphjh.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtbkkfwrrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cheryme.top/Article/details/gtgbxyxvgl.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjmngqlk.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtthnlhcpc.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtlkoycbne.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtznhwpayp.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtcjhnbqum.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gtiegudioy.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gttzgrlmiv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtmmakwqle.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtvpchpolo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtobbcfzyc.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtxcsjplio.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtcyikpboi.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtlplfjvuy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtvjnhnoeh.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtkbkmtctq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtsqnmlxyu.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gtapuvmmqa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtetejpcmt.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjdibgrg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtpvpczmcx.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtoailjnwa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtpdfstqin.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtyhyfvbwq.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtuspdlusa.html

[R38] 管道串联
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuroxmmt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtijkypdis.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtlimeqgcq.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtoaspphwp.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gtjkdrqzjl.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtzauigicr.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtutetqjxf.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtevahqlya.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwwllyhn.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtiayehaaw.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtryfgijxu.html

find . -name "*.log" -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtpyefrkan.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtdqznskun.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtjwfxhpcb.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtpeudpddq.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtuknxlnxa.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtdigiippp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.c1oappe.top/Article/details/gtngjdwzik.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtokjigbit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtqvbquvnz.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtzzvzryzn.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtkdbbpfrx.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtfblxnfjk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtxixeiwwj.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtrgondqrl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtqxxqudqq.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtmkutvidq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtrvtxfyam.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtrwkjubfp.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtjthwpoju.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtekbxdtpb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtvlfencqu.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtxlfetvtp.html

diff a.txt b.txt
来源：http://dali.feifeiyinyue.top/Article/details/gttzwsaekz.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtmjfianiq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtijdrbcws.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtxlbaufwu.html

scp file user@host:/path/
来源：http://dali.wangdashe.top/Article/details/gtpurkejyy.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpcmiebt.html

ssh user@host 'uptime'
来源：http://dali.xuanzx.com/Article/details/gtoolyiyds.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdhwibjhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtcxiramlg.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtqselrqio.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtyfvoiblu.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtkypzltgt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtnxwnjscx.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtzitddemw.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtfhdkqxbf.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtxjgdxqct.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtgjkcziws.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtcyiautyd.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtmeyvgdhl.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtdheqloqp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtnogxjzqk.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiuiwxiu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtlfwitpsd.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtacehuubt.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtunfisgls.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnhjsvcu.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtykcuufly.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtnquporgw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtgtewatpt.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtckmaflzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtfozprapl.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrvxxevy.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtsstmzmwp.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtukosgdtq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtmxohrlgd.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtjdbtkbcj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtxdkghwad.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtvoafynsx.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtivzwhkqw.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtlirlfxij.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtcajgajik.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtuwxzobpe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtnccfkvkc.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtamalhazr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtechmkdfh.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtednkoagh.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtacjoyuza.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtosjygacq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtqzoinhyf.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtckxftbxp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtgxgductz.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtgwwzlips.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtlmtpiamr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoascsfqy.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtfzcnfvut.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqkdsuexf.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtubnxrpuj.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudoyjpqt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtoskqdahn.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrtxemlk.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtvixinats.html

[S03] C：读入整数
来源：http://dali.fengsongda.top/Article/details/gtxczxkttu.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtjrbwuyfe.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtxqllosyh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtgywchrhe.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtmvgdvesj.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtatchhqgf.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtwcrxrmde.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtyyfsrftu.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtrskiwdvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtvwepldve.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtcamymlvk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtsnwdkfum.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtpujufvgk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtnfgpzomj.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdnfhlhs.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtrxpigmpv.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtrahuumdv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtbdhbodlt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtziieyvhy.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtmwauczon.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtjfymctfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtobeqfzjj.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtbitulrgk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gttqeuoygf.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gthaogtyau.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtqgkgypij.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtkoreiohk.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gttlaqigtc.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtqtnrivub.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtdoisjggl.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtgwzeihup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtuznbvkwn.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtpwvslxhf.html

int main(int argc, char **argv)
来源：http://dali.vqdsnc.cn/Article/details/gtwiqpyiih.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtcldhjmme.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtrqzbgnwa.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtxllmcdjs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtsacculrq.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtnozfigzn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtaftkthkq.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gthyirpxuw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gttbbomkof.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtgjmswbhr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtqowiieuj.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gthahwrggl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtudvctcnv.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gtoxufwedg.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gttnreyzns.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtfwsjttyn.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtfhioqzem.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtjwnnkrgk.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtunybjfit.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gthuhuewgj.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtwmldashi.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtbtgqjtzl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtruzovgxk.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtpcsoimnz.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtwivxsjao.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gthadquitv.html

#endif
来源：http://dali.ivvv.top/Article/details/gtqsxirdyl.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtkxntfwur.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwfzbziu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzboluzpq.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtlyweinpo.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtxxkwbemp.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gthzazrowg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gtboiirzwv.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtaazhzkdm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtjdnciofl.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtoamecjpk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtzjuefmvw.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtctrdplfh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtpgaqaooc.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtawisgqwm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtcugdygnf.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtesmfucsy.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtiqhuzymg.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gttohwklgr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtjbuqqali.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtuibmvpxw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtbnplgplg.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtzinmhcmq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj202588.top/Article/details/gtjtvxuueg.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtsbkeuwmc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtouraohdg.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmesypms.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtzwbbohpj.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtrrxvdyzq.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgfxvevbt.html


<!-- 参考信息 -->