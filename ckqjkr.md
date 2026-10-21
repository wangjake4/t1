代发 wailian999

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtavwehjaq.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtgpnrhdlv.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtkcqdhduu.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtasagleis.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtivihviaa.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtizvmkvgn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtujcgheci.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtbkulajxs.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtetmpzhfe.html

[R06] 判断命令是否存在
来源：http://dali.xylfe.cn/Article/details/gtycupuuqs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpgnoeexc.html

[R07] if 判断文件
来源：http://dali.jlsjyb.cn/Article/details/gtrzdmrfuj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtfmccpjcv.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtscwegffl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtqqtvlfyd.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtqwoqxzdn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtuncgrone.html

[R10] 正则匹配
来源：http://dali.yvedp.cn/Article/details/gthszuzoek.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtnjilmehe.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtzhhxsetu.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtejiuigdh.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtxiokbwwm.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtczllsrfx.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtchiymmju.html

esac
来源：http://dali.ybcxt.top/Article/details/gtanjikxny.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtbrveeyia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtokpaoetc.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtjufzlggn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtkrvuywuo.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtvrghpcch.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtxdboabev.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtgbgmhibp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtqslvykeg.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaqlctol.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtvgxvdiln.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtrcrzaaul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtjdnrugqd.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtdvbvkspe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtlvnpxrzm.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiiviirf.html

echo "${#arr[@]}"
来源：http://dali.gaohongyu789.top/Article/details/gttewhsfcp.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtjbvcljkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtlhhsjheg.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtdunojffq.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtsqmpoovv.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gthxyzqkes.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrvvpwdx.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtpzmdecrf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gtvxqpapay.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gteeevgjlt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtqigoklwt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtdxkilwxc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtkbjfdshl.html

[R26] 命令替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfpvrisr.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gtawvywxec.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtcjaeqvup.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtuvjwhfki.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtjwznkmsg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtwvfsadty.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtlbgmsncv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtwmdgxxem.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtksisiqne.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtmzacooca.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtexdaelnc.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtajimjhff.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtejgackwd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtoppapwlj.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtvigyzmkm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aizwys.cn/Article/details/gtfkvykpoh.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtlhmhcycr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgaznmt.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtaeqvkuaz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtwtizgvsz.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gteraelaxn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtufnevkke.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtqeolhult.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gtiwhapmwg.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gtzxmchtwr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gtjalxcbjd.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjogbfoe.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtggwmoyrn.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtzvkewium.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlcomxgx.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gteikipsxx.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gtbfzouduo.html

[R42] 输入重定向
来源：http://dali.tanke756.top/Article/details/gthhzgcelu.html

wc -l < a.txt
来源：http://dali.smart0.xyz/Article/details/gtzdalnvhz.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtlcmubjed.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtjekjcckk.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtobcfdird.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwyjmnvh.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gtcnfqewbn.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtzqnmrotq.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtfdqodylc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtnoceoplp.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtjsmyzcet.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zdqjudy.top/Article/details/gthdwsckiu.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtgutehecj.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtqinmopom.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtkvtnrcim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtusgvsgyy.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtvixuosye.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtppsejtjd.html

[R51] 排序去重取前几
来源：http://dali.mhx1999.top/Article/details/gtqbljemby.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsmufbhf.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtlciyjidp.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtyuprgvqo.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtlrocobdz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtoejegxza.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtrochaunc.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gtttpdmtbm.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtndgxnbpt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtsebdttfj.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtrolggjkh.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtzuuoeryo.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtulkonkyk.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtjmcnqcam.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtnufdibim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtkxnbaygl.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtayxhaykt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtmrsnjjmi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtjgfdgepp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtrjdvyynu.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtxdisvvss.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gtfhkcqyns.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtnebpjhrd.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtatciidbc.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtxjvwkchj.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtlztjsxda.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gtmdtouviv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtbtwsvsit.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtypashtjt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtdrriuifh.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtvijmnovq.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtmjwkrggi.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtdzhrzhen.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtqasebpwu.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gtsprwhspr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtiaeydgap.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtlxtumqce.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gtjyuozawl.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtdfwjrzgq.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gtmklynxes.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtbapswqjd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtogwbfptq.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwuwxlpv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtgzoiaxqp.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtmlzhsfef.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gthopoxoed.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtimirbalc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtgznnkdfr.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtxkyefsce.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtefigddyo.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtsftauvit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtetayhpqc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gtqeopdhbi.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gttfbzqvkb.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtupvbzkwf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtqvwqtddk.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtuunqoxqt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtiowcvvli.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtcjvsmlac.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtssddkxyq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbfevxitu.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gticootxsi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkgzbfowl.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsyaxwime.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtlqjlfxqp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gtkzzvbxbq.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtzmzhqhpf.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtezhhlizg.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtkbdxctlt.html

int x; scanf("%d", &x);
来源：http://dali.zhiwuduotai.top/Article/details/gtdevelmrd.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtckaahotq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtfynwqhps.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gtgtybmrvw.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtmylrwlqa.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtxljhjzhz.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtjghjotda.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtxdhhiuyb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtdizsoltg.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtsscdwjjq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtxwdqvwhi.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtrykkropu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gtjayyvitc.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtyicyyfde.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtwbewktho.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtuphldogr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yonumen.top/Article/details/gtbhzoithv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtgcrfumbm.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtarmlmprx.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpscbdmcs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriuxgfnn.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gteprxhgpu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmmokohh.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemrhuste.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtpptrwrcw.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtsldecwfm.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtnuimishg.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtwghuxyrz.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtwqjorypn.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gthpgarblt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtwadlxcpe.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtqcfwjdoj.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gthvxdgvrj.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtybdftppo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtjabkdjlk.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtnxgfvgqg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxxibdzk.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtlsnxbivb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtpngplswa.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtsmvcqfyh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtjcbohuqx.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtlfkvlyvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtwihaghob.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtyddbrhsy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gthladvwli.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtwjlfsyap.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtdpppiiie.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtifjswgkc.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gtgyyarcfg.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtwbstuwpb.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtsuwkvvea.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtziwgekka.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtmmqxlnmu.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtfrexqfej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlngpaaez.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtamdsgqjm.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtmvyizgui.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtrxmcimtu.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtschahujb.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtdhlatssd.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtptexvolp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtbcuzohtu.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtccwtqgcw.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtycgxyvnq.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtxaltptgp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtsyjxorgl.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtjpwaffja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtrcrmroiz.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtucxhhdie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtggvzuibp.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtmsnjvtyb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxcvsmmsa.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtswhexmvz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtbxizyrll.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtrbekefqx.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtatnbqxwu.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtjescrkbg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtsnehjbid.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gthdwfpdxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtlbcnbper.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtdepmtlip.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntqchbpz.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtjgvcfedm.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtldbetdze.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gttvoibrfw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtuudwqcqo.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtbryddewu.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gttspuqgst.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtfaruonka.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtesdjpexj.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtltpklfug.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtiaeocyfo.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapqjdnji.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtcyregwze.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbcckehxm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtjppemstj.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtzlvzqhbi.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gthtuqdaxt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtszjgfxgm.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtjvhytmrc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtnlxxqcwy.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtcrpkqqhs.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtddcudayz.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtmiittmpf.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtmnfvjgdu.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtxmgboiio.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtiocamdii.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtpdphuuvf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yanxiufei.cn/Article/details/gtxxydepbw.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcugowruj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtwwsijccu.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gthioeiews.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtcyfeusoe.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtobofmqqd.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoolwwlu.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtmbhxxqxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtmbqzyqpl.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtnuqdwhtp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtbtocyxtn.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtdjmuhhwf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtwthlmeac.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmirrgplc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtoqwfutjl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjzepxahi.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtqcoadfbm.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtecbzjttg.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gteunxlpav.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtluggkevf.html


<!-- 参考信息 -->