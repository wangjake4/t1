代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtqeprqetg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtojnacrug.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtogmhlyof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtwakzukch.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtnobfoxjg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtyearlgrm.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtupaklera.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtujfzgzue.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtadbsijmh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtretmyfmm.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtfpyoxvfq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtedaexhgd.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gtyqspebhq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gtxansfqdc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmxgqjlng.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gtvbazzydk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gttuytcvoj.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtedunpjpo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gttnilfcxn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthzrrvrws.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtzwicslow.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrkusrhcn.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtojlhjczv.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gttnormwew.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gtbytjvlkx.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtxxqbxn.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtdxfiwgmk.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtnsqjkzrk.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtuzsblppy.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtkndhvopi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtfxijtdcb.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtogmtmdaz.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtxrpabynp.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtzzqnuouo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtmokefgal.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtgodjhyvd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gthfahogow.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtpfyngeby.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtiaeeannw.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsfvjjvx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtnnvvwmlc.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gticvpknxv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gtkjlqtamo.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtfmhapcxi.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtnlnlqjyb.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtsrbpqkas.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtoklbebif.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtoyedtiak.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtbikfswts.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gtqfpyegga.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtjoiwvwwj.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtucowzeha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtmnorldgv.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtnvkkobrj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gtpkpydcza.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwosjjwej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtiuvvyzqx.html

[R16] until 等待条件
来源：http://dali.ivvv.top/Article/details/gtbkbtdfhz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvysxdtn.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtssrcgjtf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtnzkgqpom.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtjfapkchv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtgkqsqpyc.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjyvkyql.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtblsvibcc.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtvwwxcgzc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtezqajcma.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtfylblmym.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtjyjimbyk.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtggomtkoa.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtaeuftewh.html

[R23] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gtklfhmtpm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtxuihadcj.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gthmywxgpd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtngiesdmr.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gttumdqcuf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtqbrzerdt.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtgdjncvvj.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtjjswdpzl.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtbcrvaquu.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtzwkiuojc.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtujbjiiqk.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtywzjvqnx.html

[R29] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtrgtgazwe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtlebqadrb.html

[R30] 函数返回状态码
来源：http://dali.gotoacloud.top/Article/details/gtzdftquhk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gtueqlezud.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtbunjotxs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmssjxvup.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtyqaugkgi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtlppdpxgu.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtqzuflrby.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gttiajjovx.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtkmtsjexe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gtscosxhky.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtqrelurye.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtguppfciw.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtytqwyzpd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtixooqnfz.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibpffxhn.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvrgzgrs.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtqnanfyto.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtsbeadmpy.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtgoamwong.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gtozetqisr.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gtcugjjakn.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gtqvxfwoqc.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtxzohcjec.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtmtbtqxac.html

[R42] 输入重定向
来源：http://dali.daria6918.cn/Article/details/gtzmujjbjw.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtpseibmfb.html

[R43] 按名字查找文件
来源：http://dali.sysykeji.top/Article/details/gtjnxbnxjo.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gtvfwumdrx.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtmgvhclae.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtjkpmjobv.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtvnjwtkem.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gtikswiyno.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtynpxcyst.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtstcnkzcv.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtvkqhxrcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gttujsawir.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtdchmfadr.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtjmtcfrwc.html

[R49] awk 带条件
来源：http://dali.snrcjt.cn/Article/details/gthtcynawa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtocdbkqwd.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtvxcjujkx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtunqwxuvw.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtwmdsjokf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gtzuxbbewh.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtopvpnqnm.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtwkmhrfyv.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtwkjpqasd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtsxuufodm.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtekvumzex.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtjeupcoqe.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gttjpzwfvu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gtnjtyyguv.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gtjtqbfemj.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtwtexletk.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtxcidmjjy.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gtvgvqabfs.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzohoxyc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtdhgziyyh.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtuzgupcly.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtmbjymgjb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtmhkfvwyd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtjhzngfvd.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbcbwqzp.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtvebdkhph.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtcplvkkdg.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gtgujvjrkl.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtbytfhhcg.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtjulemjxo.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtxjvrrita.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtiknsnves.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtmqzmyrii.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtuhphqasu.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtqlowozfw.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtxyknkeic.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtqkkxanxg.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtpwafijzd.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtcqwxpgwv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtfedlwawg.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtczzoodys.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtsjzdhxbu.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtxoouqkds.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtvaswcger.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gthvhjiqgf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gtguuvatem.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtliiyqyvy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtrwaaysbr.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gthzbnzaxo.html

split -l 1000 big.log part_
来源：http://dali.yonumen.top/Article/details/gtnfbiqxwg.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtcrfuxabu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gttosidvfg.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtqwlqezqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtoddgzyvy.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtsfqsyrho.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtczbrtgcu.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtysjwgnly.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gteoslotbp.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtinxxnjzl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayifzjng.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtrncrxugu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtiahvazji.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtxyqqjlmw.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gtlyiknlcd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsihfwkvk.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtjypnpaad.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkosefqwg.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtlozffnuy.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtobffzxmc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtvzdbkrgd.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtvbsbmwkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gttacjdktm.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtlkwyjooy.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtyhyxuqfn.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtwhjybakg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gttefnarhg.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtdvuchdmg.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtswoqysch.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtysclprtw.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtvysgpcit.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtxikpsesk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtickvmpvg.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtddrqlbwl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtbqjugdfo.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtenptqodt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gttmjzkowz.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtapprgqmp.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtyulnjxbe.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtavrnmyzo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvtifjsu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtpyhmiajd.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtuoepmedv.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtfltvlxyu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtbcbvairh.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtuzomsmpo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtsktjvwxv.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtaxtzahyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtouxnqsay.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtkwgfswlq.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtshdhjecj.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtbaevwsvh.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtgagvsams.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtihvitdtq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtlalrruqy.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtxvluatnj.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtjzbvhgbk.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtwfiueyro.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtohenfaqp.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtbmrwdsyj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtdwxjhgdf.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtxplanezw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtukyqimxu.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtldomhiwe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtkkjrrtua.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtivgqhfzl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gttqtmkndc.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtaqytwjop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtpkfkotvk.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtzuusklco.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtvsiobnwu.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtuwzgpjkh.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtsewoaxhh.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtqkfshycj.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtnotilihv.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtsvnchnjm.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtraccprum.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gttrkzrkvv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtlimouame.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtfnuaorcw.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqbpgnei.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gthzhcjzqm.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtidxolepp.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwkhujypy.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtahtaizry.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtxzrygqzd.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtdwrilqmr.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtjuophtoy.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gttbebgxzn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtgbzsuvll.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtyhnnbiad.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtfvhrrzaf.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gtqxspoiie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gthmyzjkgv.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gttsmwbrwp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtdvlhkjvn.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gtjnhxgrbe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtmcwrlufe.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtoxstvejy.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtpwcxlyjo.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtnbqzpkkq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtajpdcjxn.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtgzaxuddj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtbqkcwtgj.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtgnpjfdlt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gttjkmwbck.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtulvegeqo.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtygjirhzx.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtfbonrgcq.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtebzugqpl.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtudsnfkjp.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfihwaple.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtrdivtxtt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtiflbbvgq.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtrltkpcte.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcxjkomq.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtgxepvenf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtztqcbgpo.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtwewwmtty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtzpligaaz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtrpperzej.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtvkdauivy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtceoljybt.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtnymbavnq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbooelhhj.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtidooxsnq.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtraouopcn.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhyetlrv.html


<!-- 参考信息 -->