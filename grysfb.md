代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtmclxlzbr.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtiunegdkl.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtcibowsdq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gtbhmurwsj.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtcfphwmxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtrvhzalbo.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtrlvunrnm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtnmiuslfw.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtimgcjtwd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtufiygnzv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtezrqqddo.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtssuwgjkk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtnbfcjmtl.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxtwjagx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtadvkhnjg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwhpixitj.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtntszntnp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpkzavbhj.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtymxqykfa.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtegodyslg.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtfljfhjlr.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gthxkiurho.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvaqqrzc.html

[R03] 只读变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyudubjkp.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gtfdxovkeu.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtvtsnbeqt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtqmoxajcn.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtrlhndnao.html

name="${1:-default}"
来源：http://dali.guannengcc.top/Article/details/gtfiugrpwn.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwipfatmr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtkmiceaic.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gtrtojefkj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gtwiqwewhk.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gtkxptfmgo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtbtknkmqg.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gteronbhel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtsockkgnd.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtrbslgbtt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gthuspkpie.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtpbpmvhxn.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtraouqcry.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtligmwvrx.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtyufsozps.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtskvoajpu.html

esac
来源：http://dali.cucudq.cn/Article/details/gtjvpxkmzi.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtguxcchtt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gtxrvmmnga.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gthfksvjqk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtddikyqxu.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtpxebchlg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtcrepfjeb.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtxulrnlpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtqbeomjrr.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtsbnuizho.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtjrcdqmqu.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtiujgagqo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtyzxnvlun.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtpuauakkh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtvypdhxvp.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtcuceocau.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtouoypzht.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwhksyhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtismvjfev.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtcpxvrpkf.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtvakkpivq.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtiiodqjhm.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfhksjua.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gthbzkravm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtnedxhxdt.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtfpzcuunf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtrndvxqug.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtywnumyus.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtiebxlsvn.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtcqdjgonk.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtsozdlvqs.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gtladlhdgj.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gtnrzfrhpt.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtkdzsdxkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtrcfrawzb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtslcnfjuq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtocazwbky.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtbuusmave.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtpmglqcxo.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtsfayhhpa.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangdashe.top/Article/details/gtlqtklvpw.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtvnoyyukn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtewgizkma.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtehogjfue.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtjrjxryee.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtddjyubjj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtnieuataj.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtvraqvpvs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtkjvlcamd.html

[R36] 并发执行多个任务
来源：http://dali.redwolf501.top/Article/details/gtjtyvoypi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtfojmlpma.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtdchqxhbx.html

files=$(ls -1)
来源：http://dali.316326.xyz/Article/details/gthxpyjxyk.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtvdzgnbok.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtwxnxnmeb.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtynvutvjq.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtccnjxuup.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtcjlmklis.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtezpyfrjc.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvspninm.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gteihyubji.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtchbhuagc.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtukbiivzl.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gtxadlnkpf.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtwtqblgrg.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtbneysjyg.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtamtuwciu.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtxhvohxsk.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtbupicuda.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtfrzhsioj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtzvygvhaf.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gtgokgzmrn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtijctbaje.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtpgsediih.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtcqrpkzfu.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtepssybzo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtxpjwbmnb.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtcbllrkeo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtteqwsyzw.html

[R51] 排序去重取前几
来源：http://dali.chenzaomai.com/Article/details/gtgankiwhf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gteuoskeoz.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtepiftiyr.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtjxelwshp.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtekbvuhbl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtmwnvhxis.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtbiujfozs.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtjvoudaij.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gtqftaiyqo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cucudq.cn/Article/details/gtwhsrjaqe.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gthlfchvzk.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtqmjtfzew.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtrnmsnhxo.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtuirjgdzn.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdnrmmgq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenjidiqi.icu/Article/details/gtbddurxuo.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtdilcdrqi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtdwwveznq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtrbgoqulk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocafcvws.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxvlqboe.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgyebqcq.html

[R62] 找最占空间的文件
来源：http://dali.fengsongda.top/Article/details/gtrjsniokj.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtqvdkzmpe.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gtptdzsgza.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtjlmowgyc.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtdwoqbztc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtmtjdnjfu.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtfrdppzie.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gtwhjjzoes.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtzzkyekoi.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtcqnraxno.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtbxpxstap.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gthvximpxn.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtbgaxiowz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gtmssddthl.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gttdidnjxb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtqautliku.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtancpmtir.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtpwhbalus.html

[R71] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoabmyxx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtfzvhumxs.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtjfoiaqce.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gthuywncgb.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtrahxvqyl.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtqvorigti.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtanfriudq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfggedct.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtbxpdxpjk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtbsrenxmt.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtgivydnhk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtzounlynb.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujzrefin.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqotuhan.html

[R78] 交互式菜单
来源：http://dali.xylfe.cn/Article/details/gtkqfaeszi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtznzvrjyc.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtimibeiyn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuhbnoxv.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtswnwjbpr.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtcqfzkcca.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttreomiqp.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtcmhexqpi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrtdaestq.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtgbnkrqwu.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtsrtxpbfx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtcwhdmbpf.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtsqexpghn.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gtosycmylf.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gtfuqtnzls.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtydqjipyf.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtnjtqkqni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtiulkkfxc.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmgkdyit.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtfejuoxff.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gtvtvzlglu.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtbodbipro.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqvzzzbd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtredmvpuq.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtqtgyvytj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtnauufzdk.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtwnmcqliq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtnmiwzlci.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtqauatdqc.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtbddseird.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtritxkpiv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtisxanbhx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtyuverpmx.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtyvlkdgqm.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtlqoqrxnk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtcodcbeke.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gtmdbxcsxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gttsiwsahr.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtuymrurjt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtqoaegkmf.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtedlmtinl.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtxahjdavs.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtklvindeb.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtiiocudhi.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtinkpaxhi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtwbsrnjqg.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtxpifdslh.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtqbdeovnx.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtgkabqmyf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gttfuovycx.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtkogzozue.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtcglzedau.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtalifvldu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtvmifqhvv.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtamijeeke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtmnrbdvoa.html

[S23] C：随机数
来源：http://dali.jianghu66.top/Article/details/gtrrklmmnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gtyvmzekmp.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmnqitly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtgoxhttpy.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtkjfogrmo.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtwscitmfe.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtwuoucjmn.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtmrgqzpga.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtubgfuela.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtchfjfbin.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtedeanjah.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtpeiuruyc.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtabukdgpu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtobikmtpn.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtxicxaglq.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtufpjshen.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtjzvnfhbw.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtxiuyzfsc.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtfryhsfsp.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtwtzpbytq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtcfsywrmi.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtzilmimxa.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtofjwfwtt.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtzzatzlmb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtvcdgkqvu.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gtoreasold.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtiwjmdmbn.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtjozxdbfz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtsherbgrg.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtpgqehojn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtwjubhelw.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtadchknsp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtrvesfshq.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtkrcqxzng.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtfbswyzwo.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtyyqvfcba.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtfdkutkgu.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtoebgikxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtczdpkxvq.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskrpxbou.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtoolsiwnd.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtaxhzjtkt.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtmmuwihqk.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtckvifqxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtvjlbmtsq.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtbcuazsfz.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtgzdirpez.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gtxozocdql.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtbmwndzvg.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtlkzvpdxi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnlhxbvth.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtpljzcofh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtxotxskeo.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtpjfqeaxg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtawnqamkv.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtcbmsbrgi.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtmqwzwkpr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtredzibzs.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtflmlyrhk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcotjyvk.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtgbqetfox.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtvpgrtzar.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtxhcsuueq.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtxpauozwa.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtxfvdwxjl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtstpcdvoe.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtaqfctine.html


<!-- 参考信息 -->