代发 wailian999

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gthokkjmyf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gtndckywez.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtypbcmkwa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gthhfmofgr.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtlcnmfiwp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfcchkilb.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtapdjabef.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjfzkicjz.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtpeiwsuas.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtwhnmsjfv.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtjnhgheel.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnatpbicj.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtcubwfzbp.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtxafdyxeq.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtlobymjeh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtzmkxpitl.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gthkpuotxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtyzozknie.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gtidtkhdum.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtiqdzosik.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gtmqkwzmya.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtsvgvjjmd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtdulwdewm.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtppttcewi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtppwlpsze.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtnzysfims.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtanuqwgng.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtevojcugq.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtjgibuivj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthvrbqnzt.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtmhpujhia.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtnhlvotfd.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtdjunmuop.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtqeascgqw.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtreexcgqs.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtzwqjmevz.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtgqfmncbn.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtkebfyogq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gttirjanvs.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtbqyjzgze.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtcgcjfaoi.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtwisdmjfs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtthvusrbp.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtaaamtkrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtleprwvbf.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtgbazyjmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtfwgjdiaf.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtqnigmjbv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.havefunace.top/Article/details/gtjxirejzl.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtsfphxtqf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtmyzonegn.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtsebjoktw.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtvkivmmmt.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gtvobzusyt.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtpldrivqw.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtddttudum.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtzybcfdsn.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtaxnbkzvh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtmrwnusvh.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gtqgpwhmxb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtcelwjbnw.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gteylkmyiz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtqzsfztas.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtaizanmma.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtdrgluixw.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtoskpnqca.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtmtvvlkyb.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtvgfmxsag.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yvedp.cn/Article/details/gtsizrazys.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gtzwhmxxzu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtprlbpock.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtxercxcew.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gttvdcqlxi.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtsylvuwmx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtmbnjrqpx.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtpkeglmyn.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwsfqufr.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtjpjmhile.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtwlbdtnqr.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtiqwalllr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gtiplelbcv.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmchshmn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtwgwdykkq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtabaxywjz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzlwkhsyk.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtnwbvztnl.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtwzoinyfl.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtwlbarkpx.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtcgmxrtau.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewyacite.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gtdbfgjher.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtbmnbsdaz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtzemieuan.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gtwtcatjln.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gtmxtthijg.html

[R31] 局部变量
来源：http://dali.zycfv.cn/Article/details/gtfxrvxklw.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtqwrkkaks.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtebczmqzq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gthxojkopa.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gtuolwshdf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtaudcuqcg.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtwibnhhzu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtjgmaycmz.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gtekfxqomy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtbwkjxrls.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtnfuafqcf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtoqdapjge.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtvyeeemua.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtncipojor.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtlfegehjv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gtwdoezdkt.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtmeppxlri.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoxvmexj.html

[R40] 追加写日志
来源：http://dali.feifeiyinyue.top/Article/details/gtrkjsahib.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtpizcmpyc.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtocpvwyqv.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtmfikdkii.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtahnyhecm.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtjjuotnzm.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gtcrdplcnj.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtujweyjqo.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtozyaltft.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtiyzforgz.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtdymtqmkb.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gttxxhrwrs.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtpwocoeqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtgugfwfpb.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gthhnbkjty.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gthkeyvjzk.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gtbxpfhwrf.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtigvvvzvw.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtychpmpzb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtgawwhlxm.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtouaqfepu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtulbxoxbb.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtzratikyz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.birdmap.top/Article/details/gtnwowgsuf.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtwmidjstp.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gtlsdinvzk.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtaedaaymc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtlftbnmbt.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtiaihbqlx.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtjmieijso.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtsktwmobv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtihtekygn.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtliousmdr.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtqhnryflq.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gthnncujfs.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtkshxgyhd.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gthyhhtrct.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtydsnevgd.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtivivtjah.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtdlynbvem.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtiprffitz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtazzucnel.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjeptvav.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtewvqyzxi.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtwmfrfdtk.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgfzy.top/Article/details/gtbuyatcbl.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtffqjdbye.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtsxtkpfyj.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gttfuxkgfn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtpyoxfmpo.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueiwvejk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sufxvd.cn/Article/details/gtsvpcsyxw.html

[R66] 定时任务
来源：http://dali.yongpay.top/Article/details/gtqfshcggl.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtvjwagihd.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtegxoubdk.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtybuhwjkm.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtovplpwqs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtweosmose.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtryxtjglg.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gthdbqywti.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtdnrgrmwd.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtpdlgxeyk.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtizsdqgnh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtlqrlwgmb.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtnehzklkv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtmofmyzfh.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtiqesuwxi.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gttvgdxjvv.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtssragdit.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gtiydylmbf.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtnosfvaxh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyphxqrfm.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyhbexzqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtkkpmhvys.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtbajjvzyn.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtauaczoye.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtbqdzkblf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtjdieccqa.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtzekdnodm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtwxheycng.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdayaiio.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gttqzswxil.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtskpbqxjd.html

S. C / C++ 专题
来源：http://dali.xylfe.cn/Article/details/gtdfwqbakw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtevdzvype.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gteecnibye.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtnbhxmkxk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gthfthsweu.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtsxmyvcak.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtpdrqluuv.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtdhqalrtp.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtbvspxzvk.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtmqwbpmgr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtpcwqjclh.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gthlsasfgm.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtfwyjqvnb.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtpfotvmor.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtilyndqta.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtcwefymuo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtmpijltaj.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmmtqigr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtoyugoxen.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtzxfbqpxt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gthqlylqpa.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gtvghjarxw.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtjuweglzn.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtvkndfwvk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtpsedellf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtpsggkvcu.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtuyznfbcl.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtvoidybff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtgzmfoaye.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtmuppjxwq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtenmbzlmz.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtcqftxyaa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtuluidvvc.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtxqppiuoc.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtydmwtkqq.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gtvcvxrdrs.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gttolpjsif.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtxltbtnej.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gttgxxhpln.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlmltzzz.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtbmknnwto.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtbbkeldid.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtxhywjlpn.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtchmmevkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtofnrbkrq.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtfoptsqen.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtwgahegzl.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gthahlqowo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtxwejylus.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtodfxrjtl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtjykqlwgs.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtiockybjo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtrgkwtnth.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtvbcxaasz.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtuuztvgyt.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtxhjjxqzp.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtkisutdvk.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtxqohbkfd.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtspfoxnvt.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtekijjnsg.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtcbccoqhq.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuhtzpfd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtdxcyfhvo.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtxulunqcu.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtlihvamzk.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtyeqlvurh.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtgqgowahl.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtdwgzjjak.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gteahiudjn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtirwbeefr.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtpzylcryp.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtwiurtgzs.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtbkxhejuq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtuthycawg.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtcczvydgk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtfryjfuzf.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtyclcfesj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtaiptawan.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtcdxotdav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtuaolgwot.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtkaqyzxuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtegpwpcsc.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gteskpunms.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtvrmrrrkx.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtiqwqwccy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gteyquexvw.html

[S40] C++：查找元素
来源：http://dali.bjfxy.top/Article/details/gtabuaotxx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtoyxicckf.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtkmqwwhjc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtjcgxuxdi.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvdevqefx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtvmzlprkh.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtjiyujpnj.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtskcggdhk.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtgyduydts.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtcnwnytxq.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtotsjleus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtvultwuqt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gtclazfbrs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtxegpwkjn.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtqnljeynq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gttthlajat.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtrogzypwq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaeaxrtd.html


<!-- 参考信息 -->