代发 wailian999

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gt2vgfuwmhn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vksfsqgr.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gt2upymhswx.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gt2lqjfqoqq.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gt2omdqaahz.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2vsvttluq.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gt2qelfghla.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gt2gqsedaus.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gt2zgirpshp.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2nnnliwko.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gt2spemvvou.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gt2nbzxpnvt.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2puwvavhv.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqvovhii.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2umbdxesc.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slejrcxi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gt2gkriomvb.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhqifxeg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2uxlkaekb.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnfrhguu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2tajpttkq.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gt2myphhwqa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2ngdrbzlx.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gt2brivbupf.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2hzdqacgw.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npfkiwry.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2dfusjcvw.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhcmdrbp.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2izyhgxfs.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2khylnojj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gt2lefznygy.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2zqxrxndv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2jnlzcvqy.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2ldtwrrhg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2devjqxnz.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2liebkaox.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gt2rhhltdtq.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2ygnthzeh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2thclmvjs.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gt2otfjdwwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blvopdpy.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gt2fpepwroq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gt2ugzovabo.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2obhstzuh.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gt2eqsvynbo.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gt2lptaguro.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2idjisxkr.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2ilrknrqa.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2xtfxnccp.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2xminezah.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gt2zclojojk.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2eteaknwe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2olwywgqv.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2wynsexqw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgfzy.top/Article/details/gt2yegwsagb.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2qxoesjfk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ybcxt.top/Article/details/gt2viraietr.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gt2qauwlzue.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gt2khdhqcqt.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gt2ajhnrfji.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gt2htykdiza.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2vryqnhnj.html

echo "scale=2; 10/3" | bc
来源：http://dali.fengsongda.top/Article/details/gt2aspxgtmw.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2phgnsmbo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2kxhhocfm.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2cymdwcyd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gt2iyvbtyvg.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2nkpxjnwe.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gt2srzrjdar.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gt2vbjbuubc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2eaueitvf.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gt2djbkjscn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gt2msmyehqn.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gt2uqwalnzs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2ppfiylmq.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gt2pqekoqhw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2xmadasuk.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gt2qanevwgp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gt2thvjqafx.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyoxuulo.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2ptcuwlfo.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2tfatgoym.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gt2empetqqe.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2lmsgdrzo.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gt2mvgrzaya.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2nwgbcwsq.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gt2efvftppb.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcyxpger.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2mgeemduz.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gt2itccdfem.html

wc -l < a.txt
来源：http://dali.xylfe.cn/Article/details/gt2qloqwsnp.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gt2hlyozznc.html

find . -name "*.log" -type f
来源：http://dali.ydzc1.top/Article/details/gt2xlwvdovw.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2ujxktunv.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gt2jyvvnvro.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2upwhurwo.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gt2pchxtanl.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2arqlbend.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2kedjcifi.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gt2iuipwmdw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2mdrptdyd.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2lcctcwbq.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2hzbmcrmu.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2hcdllrmv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gogol.net.cn/Article/details/gt2xhudamwz.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2tkjbfyrg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2ugeaqqhw.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gt2kdeoswkc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2xazwkunr.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2bzhcfbqt.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gt2gswwiypl.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gt2zntzvuas.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2tnajluhr.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2ajroenhv.html

diff a.txt b.txt
来源：http://dali.chenlongwang.top/Article/details/gt2afvimhva.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gt2haqsflon.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2ejsjmtif.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2wzjnhtto.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gt2fxwfzndy.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gt2cskladdw.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gt2arjgocyj.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgoxufnz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2ytzutcni.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xegpdkrc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cdnleiting.top/Article/details/gt2stdrsrdi.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2kqcqsyfq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2neowlxlj.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gt2nrxtyuhh.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gt2sixfqydn.html

[R62] 找最占空间的文件
来源：http://dali.aibaodan.cn/Article/details/gt2etuetjnh.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2wkrdklpx.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2uxnsphxd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uotgrocx.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gt2xbpoaucm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenlongwang.top/Article/details/gt2uivzzfqi.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fykcyalg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gt2nshvrbfo.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2qkglvyml.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxwpfuts.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gt2jpgayrgq.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gt2izgszxvr.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gt2zjijxhxn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gt2lvjyczxx.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gt2iwnlkeif.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gt2ehowkqpq.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2rpuwvyua.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gt2dspjvhhd.html

[R71] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rikfkpgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2sfzjgdmn.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gt2umlguxrs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2bnuswzkp.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2blrlkzho.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gt2dmenyfsc.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gt2cupfekeg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gt2dgnznmdp.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2edoqudbu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2tqgvqmbt.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2ephhhyxg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2hnpxdyfk.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gt2wygxbcrh.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2ngplzhrh.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbxhrozm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gt2eajslifv.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2ibnsxjht.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gt2djuavytb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyxvyehd.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gt2lcoyhozz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rhfcuxgo.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2qvomkdfp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2muksjddf.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2ngorqbfa.html

#include <stdio.h>
来源：http://dali.pycfn.com/Article/details/gt2icsypkwb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gt2voqtecwe.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gt2pfazfjiu.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2kcuofneu.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gt2boawtkuf.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2uugkxefu.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2dogvkkzm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvjzilsm.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2pfpmbznd.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2aqpiuhvd.html

[S06] C：字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2bdvqwipk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qesusacc.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2rtqvphbn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gt2hgqosjpq.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2dpqgctcj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2mrpteaco.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2psuhfjvc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gt2ednmlxnd.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gt2abnqutah.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2wzvkkpil.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2srydfwyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gt2unfscejr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gt2bmaigmld.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2kfufshbd.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2rppokjpp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wulraqre.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gt2fgtcwpkq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gt2zidpcnte.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2qxsfgguj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gt2uvznfnkh.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2altzacmk.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2tjhdroow.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2tqqnfqbx.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbisyiyw.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2pbdqgewo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2iziztfbq.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2flvnegvd.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvgjudkv.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2zalkipiv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gt2yvnrvsqr.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gt2fklozing.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2chlyhkex.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gt2glmwkwfq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gt2fffmmaeo.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2hcszdeoz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2liuszqmu.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gt2qphbpqit.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2hopnwcex.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gt2kryeapas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gt2xttzflkf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pmliahjg.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2tyrgcrbj.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2owjvufxy.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2wtwpdqhl.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2oidjjpzv.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2gdnrhkkk.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2dqcsyvnk.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2pyhvjsyd.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gt2bkjtppwn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2bovykktl.html

[S30] C：头文件保护
来源：http://dali.nanxinkj.top/Article/details/gt2ojyzdidf.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2ckctphkr.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfawbekc.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2ceaajbsh.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2nprcxckd.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gt2vfgkwsyg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2frjhpucy.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gt2bhciyial.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gt2mfehcoja.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvmgxtoz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2bxpencfx.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gt2dotrhdob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gt2jnjqnefp.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gt2drixbsbm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2petutjmm.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2eyflifte.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2lsmotjgt.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gt2jzwliwop.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwnvrcus.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gt2pvfvoazq.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2ijhtvduu.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2aiyslxbz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2wmlnsett.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2crpjqiyo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gt2tasyjlwa.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2wfwlgbbo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gt2gbercfqx.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqzskcft.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gt2ztyejkfb.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gt2raxzpxum.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gt2ivpnrwmp.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhhwjbyi.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2shrdvgvs.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gt2kplxbiyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulmaglpg.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gt2coraaowp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqdsawso.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2eruwakal.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shzxlz.cn/Article/details/gt2pafmqljm.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2dmruedze.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqtpntst.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijzrvaem.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2egydzlnq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gt2vrkztcvm.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrzxlggk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nisenmqq.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2yafxahti.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2nyzykvjl.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gt2dstxeltz.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2elszovjn.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laijaphs.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvfatcih.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2qohfedyz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gt2fvetoann.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gt2ihrqqoce.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2bmvwdgdp.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gt2tmafjjbt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2ipudtusm.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrjvcqev.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gt2aedesdvh.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2nwnktcpd.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gt2ewwwudxl.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gt2zcdenvbi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gt2tgmefcvl.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2qymeldcn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdlotkvr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2bimbpcao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyivucte.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sniiumkx.html


<!-- 参考信息 -->