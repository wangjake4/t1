代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtuebbabjj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtcaphefft.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtznndwyki.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtpxrmurjx.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtbtbmjotk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtkeqfzsnh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtkelocdaq.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtlelmeolz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gthznhunaa.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtqpzgsyvi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtjkdlksau.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtholhfprc.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtetnmygbl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzzcokxvi.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtdlshlzae.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtewfgdxmg.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtcdmkjbve.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtyqixcyas.html

name="Tom"; echo "$name"
来源：http://dali.hnxiangtu.top/Article/details/gtfnwhmayj.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtkpiifssb.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtjtdcsmsq.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtwvbbdkxj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtclfuvrtp.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gtbvigzaqj.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtyutxubgk.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtbonjgqcy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gthhiabkjn.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtqlasdaeo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtdrxztomg.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtqkusbqyr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gtykheidvb.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtgqvlprmh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtlrhhlbbk.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtmoakbolh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtfalsopkp.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gtaslhwvwa.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtayvmghin.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtqhykxewg.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtllzvekys.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtlggmdvgn.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtsivnveaf.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtiwzxuiws.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtlzjihhxo.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtgtehndhr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtcloivjth.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtegofoehp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtqjtlsslt.html

[R15] while 逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtldkritkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtsruibvct.html

[R16] until 等待条件
来源：http://dali.cqqwz.cn/Article/details/gtpcgukrvr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtgnobefue.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtipclrksi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtgbusrkiw.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtmrxomtie.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtroawexqu.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtponoihjg.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrqwsjop.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtrlzcedpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtfbggfbox.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtgmgtdzut.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtgwimefno.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtykdmxzqc.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtcbavcxxr.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtcvjqqwcd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gtbqnrufwe.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtqfifrxad.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gthtdbaprr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gtjjwvuvry.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtqcxlgnfm.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gttjtdsnme.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gtveyjbtzz.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gtpqbraped.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtoyzsfcjq.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbqczvrk.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gttmwgxtjp.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtccgqitly.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtkbqmaoyz.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtbauhcact.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtahstxyek.html

[R31] 局部变量
来源：http://dali.9152youxi.cn/Article/details/gtklrvhqyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtfybjgevj.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtnevtylcu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtlzxoryif.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtutcttdhd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtnrdohqyd.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfxptpye.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtvtqzihqp.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gttoljphrr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gthetxelrz.html

[R36] 并发执行多个任务
来源：http://dali.yongpay.top/Article/details/gtfwfdmmei.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtbppubjsa.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtclrdkgrd.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgaijpyj.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtekngixit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gthgjtaxzx.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtgdkhbdzn.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtqsdewbde.html

[R40] 追加写日志
来源：http://dali.yonumen.top/Article/details/gtkqslpuey.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtbkakezdk.html

[R41] 丢弃输出
来源：http://dali.dashuyun.cn/Article/details/gtqnpkujbf.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtgfuexfgr.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtgadfizym.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtvnjkzunv.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtwxudnjpy.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtbixdagee.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtdudsafmf.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtpxwxxnvy.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtuzjfryjz.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gttctfsgvs.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtwvmkrbpp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gterohbyps.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gtqmganccl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtkqqnuymn.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtoretudep.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtpapwaqiu.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtkeeawvbt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtxsawqsds.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtksqyjank.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gthuxdpgoc.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtnkgaypka.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gticvkncri.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtbpboprkf.html

wc -l a.txt
来源：http://dali.pycfn.com/Article/details/gtxwblxvod.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtfxjizsoi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtvrknbkup.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtanyyguiu.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvprudlgz.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtifczwuqb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtrshmdnej.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtoqsjtdxg.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtociebgua.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtqffldfpt.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrneshge.html

[R58] 下载文件
来源：http://dali.svipenyu.cn/Article/details/gtxykflpff.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtorkwhneg.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtojaccymq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtsrgvygpx.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtcwuzqmyx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtbnhsumod.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtxjdskdnq.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtuprpoxqo.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjmeruwdq.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtjljumzor.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtvekwxvji.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gthjjbldqv.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtzrhfupqb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtwtuzkmqp.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtkrjwwkvv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtbaqwhehh.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtrkquilpc.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtcpcrjqto.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtzewjakog.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gttwltcmoi.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtulheicgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtlagyazqv.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtkufduyzc.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtmilarbwd.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtnjbwtigv.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtiofcfrmh.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtgnouwoee.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtedyzjtdn.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtspwxozbv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtqfgkpnwr.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtvzymirpf.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqduylirt.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtonlgaujf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtgusgzsox.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtdyuexnsg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtzagwsjbz.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gtcpojxgmg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtrwlnzmya.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtyqjvfmuv.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtggqttziz.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtuqbpvbcr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtxyxlgkvp.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtlkmmdcds.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtfxyfuwkf.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjfozsrl.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtlzdujych.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtplhddrmh.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtimydezgh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdbufxypi.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtuxaikgmi.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gtvfufycme.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtztfmlede.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtfrzpqjmk.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gttrdwixdd.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtognzjtjy.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtzbbgvhod.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gttclxrgcz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtqvqgkrgg.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtbxdhimgx.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtigwotodz.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtuponpslt.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtdipzgrsf.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtdcxommns.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtgmqrlgeo.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtdnyjqrxf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gttozemqvo.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxtczorm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtawgebynh.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtfamypspb.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtpsieutxp.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtmoxwljnb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtmyokwrbb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtzzozouce.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtnorvapag.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtwlorzmmu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtnjbxtakf.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtywyodjax.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtlzjvdmrp.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxxyrmjx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtahmnqsbq.html

[S15] C：类型转换
来源：http://dali.jinqigufen.top/Article/details/gtuspgzgeh.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gtgamwxnap.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtvqiagatm.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtcwiejlew.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrlomhjel.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtwywamtgc.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gteycbwmsr.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtaphftrfl.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gtnkimlkak.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtxxdvysok.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtatcvlwhl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gttfxgchuo.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtkyvuaqbl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtmpuwilkb.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpmzyivm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtoebjtsvh.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtuekugdxv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtdazbnwon.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtkaboegly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtwymsgtil.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtrmpcvadx.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtkekkwmqn.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtvhgwwdrh.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyhbgwsi.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gthpfmghiy.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gthsgbddvf.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtiieukvid.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtivewrgtr.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gthiolwego.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtbigqsrmw.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtqczigryt.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtrwxufbpw.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtwpzeedez.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtgitypa.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtxikrttfd.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtdcywfcvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gttgqtxdtz.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtscqobihi.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtmvombwhd.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtxsrppogp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtvnfatnqf.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtaoshbstr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtuxixdcsl.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtsflzjrej.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gthlinorzi.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtdbeftpil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtzzpsfzxh.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtlehvlpio.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtzzxqitxw.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtexutnsyh.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtbxvycnvi.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtwbygyrug.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sysykeji.top/Article/details/gtokokponv.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtfdraadkb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gthoexqrax.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtyrqiicmm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gttzxcyxkv.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gtxehrpllt.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtburiqryi.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtlcnidens.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gthkruquey.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtlorcjpee.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtexvoekxp.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gthjljeyyf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtysugfbod.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtlsowuyfy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtgbjufkrz.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtnxguyseh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtdcnhdcwk.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtrcfyiaqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtvaknfhlg.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvtjnmfe.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtprsbclvd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yuxming.cn/Article/details/gtvalzvqbl.html

[S50] C++：格式化数字
来源：http://dali.chenzaomai.com/Article/details/gtgokbmpbk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtgxnozfal.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtkrrlofes.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtkeurxalx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtxocwpmiq.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtzkdnnoqz.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtqodoofkz.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtywjyhqwx.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gthgjmshpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtrzvrbaqn.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtsnfkqvwj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtagcboceo.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtmvrbksrm.html


<!-- 参考信息 -->