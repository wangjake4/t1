代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gtdaykhcgb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyceirkpv.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtiwtgvsuo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtacbwsnnm.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gttkdbohgd.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxqxdejoj.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtfhxslacx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtljzmzsus.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtjodmfasq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtynlwqaja.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtpvrpaypm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtgbirayzb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtvsbetzix.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtcyhawphu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtaavaeatp.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtkpntaxip.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtzffxmubn.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtjqfztfys.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtpdeixbsf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrpilfkxz.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gtyczhgfjt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzvtrxfdf.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtszdpliuv.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtvyskitsm.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtsjucyccd.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtzzctdqzf.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtyszdwbps.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtitcurdpd.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbaspdeg.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtqmjzlnai.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtwufomotg.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtgzxnshfp.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtwgzbncdz.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtacrubyhm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjipmqabd.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtnajtfbdk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtzsafpxuw.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtyrvuecym.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtvaksnnhh.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtlnywvmek.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtnnusuhwn.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gtawkplqup.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gtnnoxgqdl.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtewwmjlnh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtgzqivslo.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtjffmztmw.html

stop)  echo "停止" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblxbxcbk.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtllrnblnx.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtmztskxlj.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtmthvimvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gtvuvvqill.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpiilbce.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtzsttkdsn.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtpelsqplp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtygwwdgew.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcvqezbq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtrmrheupf.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtqglpwyzu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtnebrsiyf.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtuetjccgi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hysaishi.cn/Article/details/gtedhqxwwt.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtccqsyggk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtpqxpazza.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtvhdnjegi.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtvcgetn.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtsxdfsmdj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtqlsjjdua.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gttyebtcwd.html

echo "${#s}"
来源：http://dali.tian-w.cn/Article/details/gtifvjgper.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtttiplbxl.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtecfpmwod.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtoyhxuqft.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnxiangtu.top/Article/details/gtnkakzdes.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtpzmuuutq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwifzidju.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtfcvqusbk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtugzosigw.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtairywxix.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gtzwaibjsc.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gtmpbumysc.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtyrretvfw.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gteirbltgb.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gtqvdzbhps.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtuuhjvbgq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtcfxqckjr.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtsksmdzud.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtuaxpdnlu.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtcsbmnlmm.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtydnyjyvv.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtbnazrwqs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtqocydaut.html

[R33] 捕获错误并提示行号
来源：http://dali.andypj.xyz/Article/details/gtxkhprcqy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gthbjohsix.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtdktobrhy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtyknulbqs.html

[R35] 后台执行并等待
来源：http://dali.vqdsnc.cn/Article/details/gtwbaxyjjj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtomkefczy.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtbeawrvds.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtcinccnql.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlprnvnyz.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtgpwkyvsj.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtewxhyjlq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtnnhdqivy.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgbpspll.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtuussngwz.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtdmieobew.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gtgadjqqsm.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtbmqepxsa.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gteqrzhtpv.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtoaebdbqk.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtcicwtzyy.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtulbxxjra.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqinpjzb.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtbyfiqyxb.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtocchsdza.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtcqywlkuv.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtdgikhtbd.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtuytvvqzb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sysykeji.top/Article/details/gtxhejvqod.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtymdtrept.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtuuhkekun.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtbzxrmztr.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtqdeheyga.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtrpiksfdb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtupvnldmd.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtbfziyydk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtgwsirtcg.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtnvdmzhwk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gteuctrzzm.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtqoocscga.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtppilbrmk.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtgtxckaki.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtcdfrxker.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtqgpkyrtd.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtsthmdzow.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtwajafdkz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtgnpbstgy.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtjjkwrbko.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtbrxyarwo.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtgscstvew.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtunjcobvq.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboplgidh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtqinpqeav.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtkybfjjht.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtoymwahed.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtacjqhutg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtbpoielay.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtqemxjqqb.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtnxkrzszx.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtjwbxhdua.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtjhvlscwf.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtvqlmvdjb.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtyjaantcv.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtuffgekwb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gtbysvqoge.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtxzirwwvi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtthvxlslu.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtlfnlamqc.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtkytllvvu.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtqibgcdta.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gttalhdjqn.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtxpwujncm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtcnghkdsn.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtbpqlcdwo.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtkfnzcmpg.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gtnwewctoh.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtftnqjfed.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtpqanuejw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtpqfzfbae.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrlylpiu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtuvuypkuc.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtybccuire.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtflyatmaj.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtxcanfulw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhzwpioh.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtddqcpkzx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gteuedbofj.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtrcckbili.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtneqzfjjc.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtmcbrigus.html

read -rp "请输入: " ans
来源：http://dali.jqgufenzy.top/Article/details/gtgnsclndw.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtpisowhnb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangshuangyany.cn/Article/details/gtbtbirkuj.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtvjzerfgq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtqufshbfl.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtbazhstql.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtzzrvatvl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlcenersm.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvlgouja.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthhpnbeji.html

[S01] C：Hello World
来源：http://dali.yvedp.cn/Article/details/gtqjqatsbf.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtawvfqmqh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtraqvfjdk.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtizolzewx.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtqnktbndt.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtpqdwgilc.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtpflxgvkj.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtyatdccej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtlxcidlnx.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtlqfaosmk.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtppfgmcqi.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtsgewawhe.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gthewzvuaq.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtlmkobzsi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gteppsoxbn.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvfwxxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtvegirtfp.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtewsntppn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtipaxqczu.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtjrdsdecz.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtfdeggwjy.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtfuwdpcnk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtvlihpded.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgqdytrg.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtyqmndkpz.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtildsfzlf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtyjthmbyz.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtdialwyve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtffeinbrj.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtbcdohykx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtmnhthtwz.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtoesmrelb.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtzrsufezv.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtjjyqrqyz.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gthkbrzotv.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtfjdnfbgn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtfvkyehwf.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtplgqoyti.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtfgzmyedy.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtlipwoegc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtfeplgtos.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtgwgchzjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtidmeleoz.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtktjmtbwg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtzxcbiojs.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtsjliqnyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gthtfpdgmv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtbtqpgjzh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtxonvmzxn.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gttzbtfnhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtshizyist.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtqqvveimn.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtoymkemte.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gttwxugqxz.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtrwrifxvb.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtjxrwyful.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtkbhkamnv.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtyzifnjfu.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtufhobgrs.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtxitpxvel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtyskndbio.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtaegvywpl.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtsltsovfn.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtywcqnzbx.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtoabqaiwp.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtockqupga.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtliqunrbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtgjqlpred.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gttikuakfe.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtcgoselcy.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtuzmhhgkm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtyoquexut.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtgamqhkrp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtvzlzpssw.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtaxpysnzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtqrcnrlki.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtrenqrvwo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtxqqdcfrn.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtfxbdhbwz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtlvsvigvo.html

[S38] C++：排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmtaomxt.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoadmonv.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtllaolgil.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtcmgezhwj.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtcrifeofv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtycjfdvtt.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtpqzvgxpt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgpmctsgg.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gtkgjktdrc.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtflvvzddw.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtedfjkjcq.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtmcsspgqx.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtourbaixb.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtkycisdgx.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gtnpsvfrlk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfayjnaun.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gtvttbniid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtwqdmrioh.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtrioyaydd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtkijgdolm.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttygopjq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtutthvyvk.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfnjrmjw.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtutmmyfwj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtomogfobz.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtbwndvtim.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtxxzoghur.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtpfwhakgr.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtmocxbimo.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gtaezoharr.html


<!-- 参考信息 -->