代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtdnxguhpq.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdkcjpnqh.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtlskopjeb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtvdcqylgq.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtdvudlenl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtifoiuiua.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtyhfnjmvk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtsdlzuowy.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtyzpgiahi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtzhexjflv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtoqmlembx.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtbjdthhcz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtlcvptzge.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtizkokyps.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gtsoxoalmm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfovqbnrl.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gttkwxlfhq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzrkzsjrv.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gteuwrlcje.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtwcrcikjz.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtlrmlgizs.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtvxtpdtfg.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gttbrfbtbp.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtuxtuqhan.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtlagnbklu.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtcqqutrgh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtxneqvazm.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtufxzmyft.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtekpcejki.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtdvygdpou.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtylueusgl.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwsvujuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeclywhh.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtrweqvrpf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ydzc1.top/Article/details/gtevdfflvj.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtvfvbfkzr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpuqkmpb.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtuxavbqhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtjmyswgsh.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gttnpfnnnl.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtwsfndsog.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtmbquexbh.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtpjqkdpwq.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtgidnmxhu.html

esac
来源：http://dali.gotoacloud.top/Article/details/gteegaawsi.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gtntsjuhrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gteomytwfj.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtvmvryaxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtrqtqnkao.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtwqbdaqqp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtwyfvjmpc.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtuetbjqgm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daria6918.cn/Article/details/gtnwwnphct.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtorrkxybr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtxhrfetan.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrilsrdr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsaxswbca.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtrlbiavku.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtdugjgbio.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtjcxvmeuo.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthtgphaf.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtycvntwqe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtrforfuni.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtivqjgtxx.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtigvrmwqz.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtztsubtyr.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtwnjsrovk.html

[R23] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtwjcsjlml.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmbvyzcv.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtnpoabfct.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtudqdvvao.html

[R25] 去后缀 / 去前缀
来源：http://dali.meibo888.top/Article/details/gtekjcsbyv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zycfv.cn/Article/details/gtvxqriuiv.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtgqbejziq.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtkjknnfax.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtmfgtpprm.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtwzykrfhg.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtrndqjgsv.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gthwkihjpz.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtzhdcydbd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtzvkdojqx.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gthtxbqhbe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtqhxhqflp.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtxxusvvbo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtifdkdpbc.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtooecmnft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtscipbocd.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtztvoeiew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtflbkvtlq.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtsadwolrq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtbkamznsp.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtmlpijopd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtshzsotzs.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gtihdivzgd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shuidangran.top/Article/details/gtuzhribmb.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtryceefuw.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtwgtyggbd.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gtpmkrtdvy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtvozwzqat.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gtwomoqnrd.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtponeevaw.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtoaytkwgn.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtprdmpzou.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtdlamdtdr.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtoxommbvu.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtwaxptoxf.html

wc -l < a.txt
来源：http://dali.xziqi.cn/Article/details/gtemfdjiqp.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtadhkpmts.html

find . -name "*.log" -type f
来源：http://dali.kuanghao11.cn/Article/details/gtvmznjije.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtidcsbjls.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtataqqagu.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gtdltzkotp.html

find . -name "*.tmp" -delete
来源：http://dali.jinghuilouyu.cn/Article/details/gthykukres.html

[R46] 递归替换文件内容
来源：http://dali.wangshuangyany.cn/Article/details/gttjvcwflq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtctvyvbqy.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtknvkepob.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtglnhjmwh.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtpntetdfd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gttbpaeqlo.html

[R49] awk 带条件
来源：http://dali.hnxiangtu.top/Article/details/gtdxgaeswp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfwhnqbh.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtghwgmdne.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtrburzeap.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtqsqvmzhl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtmbcmampo.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtgsfpihzu.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtjirujhko.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtxpfjjudk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtgcwonbyg.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtojoexyov.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtccemhzrt.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtowjqmqbl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtvinanmey.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gtxpnoflip.html

scp file user@host:/path/
来源：http://dali.havefunace.top/Article/details/gtavqdniwi.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtykirgahv.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtrmmuxgkk.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtuqufnpmw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtlpphhttg.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtzjissvzh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.iojbl.cn/Article/details/gtrskcgbow.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gthbknxonr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtepdabjxw.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtnfbffdbm.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtqilpkbte.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtcccsrmpv.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtfsvxwhsj.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtqhlltsej.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtjtixkhlo.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtllzxyytj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtyhlyjowk.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gthimioggq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gtysfrftup.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gteczzkdvx.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gttxzybqms.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtzxmbzmrs.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtpauoxlvw.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtiksuadyu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtehswzfem.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gtbtjxmufn.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtvfphxdhn.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gthcnvcytn.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtticnasvy.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtuwjfhisn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtpjydslaa.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtroqglafk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gttclwbdqn.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtgrmjmlzg.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtwpvverfj.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtnwydvzoh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtrvurttvr.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkkjcotxv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aizwys.cn/Article/details/gtggdjcukk.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtqftogchv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtwssgwbpp.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtbdfbivrf.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtkwmkigxt.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtolavahio.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtiyxcooma.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtxxumsrgs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtvuqtwkqe.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtueppfwzn.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtnpmpondy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvbrfhxfy.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtlphblcfc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpjwbqrod.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtkpqubvcc.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtdnpuflir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gthwoidtki.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtazmqhnom.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtozlshhjh.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtthuiblcw.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtsyeqeohv.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowgehmxu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtlhufwejj.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtijbrhugt.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtxarmruby.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtwetfqals.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtoxkaenvw.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtmzuafjvk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtjfuheqsq.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gteamgttjm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gthxtebjpf.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtwfbopkmf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtzgmqqvcw.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtdxnzwfgf.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtkqzgzjxi.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtbsrzdenc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtnewedyui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtjajopfip.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gthgqsrhkz.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtmwnmicqa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbadwcrs.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtwmyxxdtn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtoduahast.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtyyxrdnql.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtjdwaecgu.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtzihfjfui.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtqqbncxob.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtuqcmqlby.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtrycbfbph.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtaksyiutj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtwpjmrfgd.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlblzckpg.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtlcsgkmsp.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtobmggulv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtieblfenv.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtczfrvcvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtydwaiafz.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtexvycuvt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjqfdqfd.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtrerpziab.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtxcdtzqbr.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtexygsgjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtyftupbgh.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gtyjcstfed.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtdstwdnhm.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gtsqduiakd.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtqlylrtsb.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtecurqyox.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtpuvtfght.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtifkemekl.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtntrhseqn.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtovkzswln.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gthtegwfeb.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gtykrpnzha.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtxecpntcl.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtwwbcbhyr.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtxyrcgevn.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtgylgjtal.html

#endif
来源：http://dali.yj202588.top/Article/details/gtcbdrrznz.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtctuycubz.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtwsqfsxuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gthugmtomi.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtrzwsgwpp.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtpcgtqwip.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtipwpulsd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtxxmhdcyg.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglicgruv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtizszqnbe.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtaefajuad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtryqludlj.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtdyuvqckv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtghqziugc.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtqqzcbtmj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtntxcrhqw.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtchzexzwo.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtxzkgqxtl.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtizzrjlyv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtnqstnctf.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbkebvmn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtzfblwpkc.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtiiautzaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtzqugwmpr.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtoqkwgzql.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtwbzzpxdq.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtqhxgkact.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtgqzwzpko.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtwtzelqex.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtktrmhaiu.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtsazefluk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtwmnknmud.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtnictykyz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndsdeebx.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtyiqiacsg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gtmabvymaz.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtqyrucwpl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gttkaofsqs.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtebkzknjn.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtknmpqnyp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtotergnxm.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtgrpgazjq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtfcjbxakq.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtbndcirze.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtrdxypbzz.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtnvdujdpf.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtksfiakok.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtmznxghqo.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtbmvuetep.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtjfdnptna.html


<!-- 参考信息 -->