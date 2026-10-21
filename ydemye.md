代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtgmzihuau.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxwbvrgs.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtynijovfq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtlhkbjspg.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtkyrvrezh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtrlrfsget.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtjzdaurwe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtfacorohg.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtzeyqfeub.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gthskxwlrg.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtwgvzrmmf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtoeadkhke.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtvzfhyqdw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtybaefdck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gtmiyjxzlr.html

[Q89] 判断表是否存在
来源：http://dali.hfpthk.cn/Article/details/gtkqevdsby.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtcrnfjmhe.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtskxjebrm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtmyulglrs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcgeumzmz.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gttkdxmcgb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttyzzvxjy.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtfagdobrd.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtzjidgsrb.html

set -euo pipefail
来源：http://dali.feifeiyinyue.top/Article/details/gtexikvtho.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gterprskxg.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtzwxvacwo.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtmixlrvfg.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtfjroqzuw.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtxplmrexh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtsloptndt.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gtpwzssndd.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtbvooqzbz.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtaczezsfw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtfegiyewj.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtmuyqrqho.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtzphmvpvx.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtxwftvyri.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtvsxwouom.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gttrjduizx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtwjpohyus.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtmpfrthyn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvurxdwp.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtmkrodcoq.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtukqbjodp.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyulxhm.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtzqjfbqdy.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtfikmfmwk.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtptkkwqix.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtzvovqefh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkjegsfw.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gtffiynwls.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtvmrbhdjn.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtjiiwyzoq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtgqnbywuj.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtbpjptqku.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtrhouaclt.html

[R16] until 等待条件
来源：http://dali.hywenlv.cn/Article/details/gtamnvpqax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtckwjktnw.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtpvnvbkzw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtkqfbodvr.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtylczyryx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtfnrhbsfa.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybnirjpz.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtdewjmutq.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gttkduwjlv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gteqepwjkm.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gthgefocgr.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtdntryxmq.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtdtbfjgzr.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtcewfenqd.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtmdqwkqxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtxjigbnej.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtdzooonqy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtqufysvgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgfzy.top/Article/details/gtxziazkxs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gtycmuvnzo.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtvjrqcimy.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtpbctqkkt.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gtqiviipaq.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gtqfufgixe.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gtgobdmtdh.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtebqqjtqo.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtsmibwwxs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtbywcsdgo.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtqncoeygp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtjziieiay.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtetiecypw.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtocodiefa.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtsusxleaq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtghzmsemb.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gtgwzbvdlr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtyuxitqms.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtfcrydy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtzhoznnzb.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtavlilmyr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gthfawfyag.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtzdzmgsoh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gthitwxozy.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtijqbmjqt.html

files=$(ls -1)
来源：http://dali.yuxming.cn/Article/details/gtvxsijaun.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gtqwslxhkx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtfvbdagno.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtuzpvczqf.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gthxkofnlz.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtyoukqkot.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtcdsarmvu.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiaqvqfb.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtruxcuwaw.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtvvpfmpea.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtxpafebfg.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gticvxnxzx.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gtkjdszkjj.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtarlmlqoh.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gttcdcedgl.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtsnhwrsjh.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtcbwgibll.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtueesesbx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtwesbqpvb.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtxvqlihtp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtemlidckn.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtcwelzrcr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtqvkwrmca.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gthngrknwr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtttvkobiy.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtnwxiuode.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj202588.top/Article/details/gtpzirtzcd.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gtekurgeqo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtgkssqgot.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtjplvxahi.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtjajiywnj.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtkmyssqgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gtthdojxms.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtxayabgim.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtfvhdxkrk.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtmmzhxjkt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtqfwikbiy.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gtwhmhtysv.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtolgdmrgw.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdtfqbcw.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtqvmhaxox.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gthrzpjgye.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtamosvkvn.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gttzyeogif.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtnnqzslpz.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtmlftfwmk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtnqrymcyy.html

[R61] 磁盘占用
来源：http://dali.jiagoushi.top/Article/details/gtgcrhbqqg.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gthowvugfx.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyuqajrwh.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtueirmvnk.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gtlbzfybre.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtzrfcxlze.html

[R64] 结束进程
来源：http://dali.cqqwz.cn/Article/details/gtjuwbszmh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gthhzyuyme.html

[R65] 查看端口占用
来源：http://dali.xuetiantiany.cn/Article/details/gttmhokygh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtfpvxygnp.html

[R66] 定时任务
来源：http://dali.hfpthk.cn/Article/details/gtzrilxexu.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtfwpboehj.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gttdrhpwoy.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtmhdmrzjp.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtivafcndo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtbryfjgnz.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtooelaplz.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtdxptbgfc.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtwuwbonoa.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtstqohmkk.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtokfnkqlu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtyybqcnge.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtnivjgdmu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtcdrxtiwq.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtptnxknal.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gtntjiuipk.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtvubxpiaz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtovvzzzld.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtelfshzhm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gtkppvnboe.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtinugvuob.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaufdkyf.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtysvlvvoz.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtslxntgoj.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtlrkpeahz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gtnodidyyu.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtvqrsvfcp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtokeingap.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtwmnzxebc.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtvqergugw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttolrohgq.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtvgfhxrnq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlwcxdmyj.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtwgmdeaff.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtobhjuufl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtxtasyuah.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gttvgppafw.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gtnpkqtgwx.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtxdmkbkue.html

int x; scanf("%d", &x);
来源：http://dali.chenjidiqi.icu/Article/details/gtamlkxlxb.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdmeiwnv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtvkhylnia.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtvgbmqwiz.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtggjoyqxu.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtvohkgoha.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtozphneem.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtmldkmbnz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtjguvbmpq.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtekvxdlci.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtkgzutvjg.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtmldjafji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtmbfkrcme.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtkgegwzlj.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtoriupxag.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtiabdzfry.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtlzccwbjz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtixrtkvzz.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtvjjkjbvu.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtbsbjnnwz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfosyenax.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtgmmfigsb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtzrrlyhqj.html

[S14] C：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtchzjfwro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtlrwzbqiq.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtcajiheds.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtuurqmfkh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtdrccwghr.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gthnelyvig.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtrvxjzcrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtdkprsnef.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtyzhvddpe.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtzmweotop.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtbhsflatq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtygavkjsn.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtnnndvioz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtwtvjwsnq.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gterzemnmd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtlycayxtp.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtqtxaqiyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtnmidotzq.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtpjnglktv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtxoeahpds.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtjaqrdggb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtqucpyypr.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtpvnpigvt.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtwelwkrui.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtramvzxyl.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gtklkceppc.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtrpvivphl.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtioybhvdw.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtmkcxwjgi.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtisrnlflu.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtnjebzsyp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gtkywclcat.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtekxkmywc.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtsqkqiese.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtzhxbiepr.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtqhcayohy.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtjnmribqu.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtzgtzyzbu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gaohongyu789.top/Article/details/gthvusgtqr.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtnoneenal.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gtjwdgawqu.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtikglptzv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtekfdvivg.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtioaryeli.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gthyqgnyzu.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtrxwasaqx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtqrqqlgeg.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtykvelsal.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtwyhzbcof.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtumeeabsi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtwemsykvn.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gtzwuhelaw.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtgkesgtvz.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtusjpcmvg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtgpuigxxs.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtkrewvwsa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtekrocmko.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtikiospxv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtnzkbqrpm.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpttckdyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.cqqwz.cn/Article/details/gtwtorajco.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtglgvumcv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtyjqvsqta.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtzaqewycr.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtmgumbwmc.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtgpqrhmpp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gthpfhayiv.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtpdbfzajn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jyoumei.cn/Article/details/gtqcqaskwg.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtxqduqqij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtflzczgkx.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtdeyyuitf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtmfzlqijt.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtbafeetco.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtxvrjyxpj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtrwvpzlje.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gtbrixrsek.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtkphwkupl.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpvcbwqm.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtclmbhouf.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtfcfshrci.html


<!-- 参考信息 -->