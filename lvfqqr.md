代发 wailian999

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtyvztimzn.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtusopdbtr.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtphgkzpvt.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtnrvpkuva.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtflhlcsir.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtgeghxhoh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnpmchea.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gtgpfxzrcq.html

name="${1:-default}"
来源：http://dali.hywenlv.cn/Article/details/gtolvpwhgu.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gtmvqlvsdv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkyxdlxxj.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyxoakgl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtdfjqoryl.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gthkrcqjtf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtvntrsawk.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtkkixoyyj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhengqikj.top/Article/details/gtetzwtner.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtjlcjgbjp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gtmgbahlig.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtkocashxv.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtyvhzvkjn.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtnzlrjgml.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gttfyhvaki.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gthkpmjkfg.html

esac
来源：http://dali.iojbl.cn/Article/details/gtzlbgpfzf.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtxpyioiti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtbzjgezgc.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtckawpcxb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmaixdrd.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtonphxbjy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbegnclgl.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtbdcbvvib.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtugxbydcx.html

[R16] until 等待条件
来源：http://dali.nanxuanxn.top/Article/details/gtjpudbrln.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtejswrtto.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtixgokojr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtelbmdqsb.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtkuvslitp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gttlylunkt.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtjxqfevnq.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtzspovjep.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtmayugwhn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtheuwiykb.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtmmeoyida.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtrruzhtke.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtvnhradro.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gteczkeuuw.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtilenqspj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtoqyybogz.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtegnotkxs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtrsnehsap.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtkjlgkobw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtcjoojfsg.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtzpztdwif.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtuyxyrphk.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtrpnnquwk.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gttjsionwy.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtmxfolxze.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtmzhflakh.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtqfzaukid.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtitekveju.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtyfpyhpxd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtxpdeneei.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gteszhqtxc.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gtvpfgyewo.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gttuauvjzg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtgnwxwpix.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtlxqiodoo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtzepxlliv.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtblrrgfpc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtsorplhrr.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtkhsleerc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtnpdmeaiy.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtaielfkib.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xylfe.cn/Article/details/gtqloqpeqa.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtfxmtvrfj.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtzdbdunns.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtmthlzoqn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtzgdarlwe.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtteohbncs.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtsaxacugi.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtfeonycvy.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtrxguuwue.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gtaylanjmf.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtcetsetaa.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gtuvrlbbea.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtwcgnhfao.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtniqhjwit.html

find . -name "*.log" -type f
来源：http://dali.ivvv.top/Article/details/gtnplsvomt.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtxqgyaoeb.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtlqndxqnd.html

[R45] 批量删除
来源：http://dali.cashguo.top/Article/details/gtpiulikuf.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtokokpoer.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtnttjcrxr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenjidiqi.icu/Article/details/gtkzpwfcvs.html

[R47] sed 单行替换
来源：http://dali.gaohongyu789.top/Article/details/gthfcyrpcz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtzsbccrlo.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtyjlzktkx.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gttpdpzagn.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtbbnhprxc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtxvmuvbpp.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtrwowazai.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtnotzxuzf.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtybxmcxaw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xinyue.icu/Article/details/gtglbfcdtf.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtupvgtvbc.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtvwabvnge.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtvvdxqace.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtimefkgfh.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtztllfvmw.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnvypensp.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtjgqkcvkh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycwxfrqb.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtlnrqkraz.html

scp file user@host:/path/
来源：http://dali.hammf.cn/Article/details/gtlvkzpebt.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtslvuezhv.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnxrdddk.html

[R58] 下载文件
来源：http://dali.yuanzhike.top/Article/details/gtrkaycnxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtrqyyjtkn.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtfhrsffcm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtwvsiyvfj.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gthwcwhujv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtzxxmtlne.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtgxxnnpjs.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtwuwitmat.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtkgbamcjz.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gttxjsiung.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtstevkluh.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtovsmzcpc.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtjjlqfuxe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtqtzglseh.html

[R65] 查看端口占用
来源：http://dali.feifeiyinyue.top/Article/details/gtxqhkbiye.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtvjlwqkzu.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtruylzapq.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtqihvoehy.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdtkasow.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtfzhutxze.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtpjaxhcei.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtrtmrgftw.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtfzdlaeda.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtvxosnvol.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gtocrboojv.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtwthrukuc.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtcmfxvmcp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtpvwtfkqw.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtnsxhvzfb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtvxihblcr.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtigbewubd.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gtggwdxbzh.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtfcvizdte.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gthzgkbbui.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtoyvuxfjb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gttvbkepso.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaspqyrgs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtkexvdhnm.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtnmrytrvu.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtqbaybyjx.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtdklfozwn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtpjmqmxrz.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtsxpszkwq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtymybnqmz.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtpcefuhch.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gtuehpbmxm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtescltbug.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtoikegnhz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwkmrwzwi.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtkdjrlnwf.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtithxbmvf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gtdqbtlmpc.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtnggcvfey.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtcpkwyfuc.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtvvsjdzcp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtvrjrimlt.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtgjvctkec.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtjykjeawq.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtgugzcoem.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtupfxmsch.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtxnetxkmq.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtwnjmcatv.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtxwbfgynw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtugunbwuf.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtqgkqenmn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtkqgoylnd.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gthvfvlhto.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtwaiojulz.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gtfprxzmqt.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtbmzpnxvn.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtfyqxbxwg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aibaodan.cn/Article/details/gtdbmglnkm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtmtkkyemz.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtoilkqfow.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtgzqlvjaf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtnxhmpaho.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtoebhwdjo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtuwxpquqh.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtllwmagnv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtkcrpkpst.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtnwjpclbg.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtfiseedxw.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtttvecvee.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtjmmaojre.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglwcszuj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gthfpntxyl.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtunfcbkgq.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtewrohzzq.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtzsfnegmu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtrrrctkoi.html

[S20] C：二分查找
来源：http://dali.9152youxi.cn/Article/details/gtoiiducrd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtkihutvkv.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtftcjhqje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gttdgbhkzs.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtmydiottz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtobidmsil.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtlhswpaky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtvugdkylx.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnkqadhs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtwdloaxhx.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtzdbkmpql.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtdsfjgacb.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtasjhaakn.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gteonynbjv.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtvaanugff.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtzdcanoyd.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtdmqdowep.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtfmxumouh.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtvgstcbch.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtdppywkem.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gthknbjksw.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtrsehmivf.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtdasoardz.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalergdtw.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtaaybnmjv.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtterehbjs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtvwwysbdg.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtfofwjdda.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfnomftf.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtjdjrjbse.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtellttsqs.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtacllitrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdewgycyc.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtonaclnku.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtbbswpovq.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtywlpdvsb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtnhejnyew.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtfwsfuyfe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtxqlhmfoh.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gteiyjeshn.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtgojiypmx.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtaqrabbwk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtijytctxq.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gttxwacdkf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtnjaofigy.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqvzkgjq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtvhekoylo.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtzpssdtki.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxkoivqi.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtfgrivjmn.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtqqwqcmnb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtcerevmtg.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtwtmzrirp.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtgxmzpsri.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtncjwimiq.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtshbvbjvp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ehwqpu.com/Article/details/gtpvsihfgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtpowstczu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtkxnvmqfo.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtfetmphrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtfhimybte.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtwvljrxnf.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtrcphfewh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtqhblrqyt.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsmedptj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtbjazlzrx.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtphxfybqd.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gtbnctnzkf.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtrtzotwyl.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtdavmxegv.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtxlycybuc.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gthzsodggl.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtyistzjio.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtdskinrea.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtsdqtxreu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtghgnzyog.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtpybnmurp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtflmbpikm.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtvhfxedoa.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtxngrewnh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtlrswwtzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtfzoxnzzq.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmvuvgsv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtvvfqluvd.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtvnhhymqr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtbbesfmoq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtokxwjnap.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gtqztulkeq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiffhxsea.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtlezvebcw.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtgbhlawft.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtygoxcfxx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrpsbhmo.html


<!-- 参考信息 -->