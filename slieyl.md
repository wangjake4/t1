代发 wailian999

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwretfdc.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtgtmseysn.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtxtpbiife.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjiddjldf.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gthxhuvidf.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtftmuvfoh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtzbkuoszt.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtoezofksx.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtvxrnikfa.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gteztufutb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtnizhunpq.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gtsjljgscv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtagmcxepy.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gtrobvsmeb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtzxhkvidx.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffkalrqw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gthebiwuji.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtaxxqdlnh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtuiqrlidc.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtsnydcsnp.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gtwsnqfsps.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpeutvns.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtvdyisutn.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtirzvaszs.html

esac
来源：http://dali.tanke756.top/Article/details/gtjcfttlbt.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtngzyifqo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gthabadyqg.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtdqzgtxru.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtszknttmw.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtqbkomota.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtnwlawwlw.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtfhqteapr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cqqwz.cn/Article/details/gtsdlcowco.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtijirczww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtunvnawlo.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtszxuprbl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtsnkehssv.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gtkgofbhke.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjajxtiyx.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtghnlshki.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtuidkiacf.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwmxlbyd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtwuxhvncq.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtvccdwugk.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtmthxryth.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtcrnacbmz.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtaafqomkj.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtrmrfbxnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtslojdyca.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtcnqeoxte.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtdxjmdvgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtbqqdpcbc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenzaomai.com/Article/details/gteduggnzd.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtdmweyvfy.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gthpxkuepx.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtkwdhcuzf.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtwnhskwdm.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtdvxtitqc.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtauvxiqhb.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtekhclkxe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigufen.top/Article/details/gtriknmvsk.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtvujoopec.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtxpbrcteg.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtremuiqoo.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gtillrsrym.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtkwutxnrx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtnhimiczt.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gteoxzckom.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gthfkmymdc.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtswjcxviq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtxssscrki.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtncimedjk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtdvsezxgx.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtghkxcbfq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtfjiupjfs.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtscjpejnu.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtcnvhebdp.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtwtozfhoy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gtrtyzdlth.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtntwtfcai.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtbsvjzngj.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtghvkpwfm.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtvpfdtmnh.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtvrsnqfbk.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtfjmeqjcp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtxfstnapr.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtxudkheok.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtyqszrykt.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtvtrtyrxm.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtxiegoqsx.html

find . -mtime -7 -type f
来源：http://dali.hnxiangtu.top/Article/details/gtqxxyjnhx.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtvqsqgezt.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtecqablaa.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gttqsqliol.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtyqnyttlp.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtgzexmuni.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtckqkxtxp.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtdbdefspq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtqpbosunb.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtnrkmjnbg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtoqvfhjsq.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gttnbhyjos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtcquthxuc.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gttnagcrln.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtyrmbxvvq.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtcvhixtzk.html

wc -l a.txt
来源：http://dali.chenzaomai.com/Article/details/gthmadxses.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtlebhorsq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtavyrbpqg.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtcmfenwmo.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtapmrdwui.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtlfzwqokq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtygavarrn.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gtqmvqhjjg.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtnlmjtxhk.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtbcxmnqtt.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtrebofvey.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtzfiopjgs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtbvhznjvh.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtcttktwlw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtdagenxbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtuunbpcwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gtswokzvep.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gtsinmxaeh.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gthdkfulmr.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtnpkjztlu.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtxyxmtbsh.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtgudwmqsu.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtajqlqrwj.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gtwvbnjpyh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtdorerjwx.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtnrmosgbj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtalyexqok.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtvcxzwhzc.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtlesghspj.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtqfxfulqj.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gthxqwbrpw.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbstdbox.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuxming.cn/Article/details/gtjadfwufw.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtrmeqpvdo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtbdqebpfs.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtboqxqzen.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtmwualyuf.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtsynauhcx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gtmpbxbbkj.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwxtpsns.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtuzkrhyvr.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtftfsakmi.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtdhpowlbl.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtqlvieney.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtwzxicenr.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtzspupaby.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqogspzwf.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gttiqnragj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtobeviexy.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtoxndoyio.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtwmenqiao.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtvnyanezu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtbavcmuih.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcikvpdrm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtvcelgucl.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtfpsakjyr.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gtrrxdrnhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqbtkxnzl.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtlndglehn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrcnusyax.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gthyvzvtlw.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gthjqladvl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtewvsmkiy.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadcsdwzb.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtkpgxgzgr.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtxwgsqtzq.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdncjhhua.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtbutztyhb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtpgzcrmtl.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtyrlezrei.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtmnndlned.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gttoxphmmp.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtplwcbqbh.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtjybnadvv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gtolgmlzez.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupxwjrcu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtrcbkkval.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtsawpbcfe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtngaykubw.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtvhtphfax.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtjqcitezr.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtzjqxmwbq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtememwhqk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtpevaxndr.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gteefadxul.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtdzvdgcyd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtciezvfwy.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtsiktrmve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtyhbgrgkq.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtvirsfmfg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtuoijcsob.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtttovoppu.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtxiykgmiw.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtfmnviwwe.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gthfkrhqmv.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtkzcjpekd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtorojqrir.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtfqwpyefg.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjbgtaqc.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtbsmznytx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtylxwxlfu.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtiluesjjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvwjmdwm.html

[S21] C：字符类别判断
来源：http://dali.fzhhl.top/Article/details/gtowefjeza.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtuataoxuy.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtsiqxnytv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtlowdhbji.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtpmqvvzqj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtflghiygw.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtfclctsrb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gttqxuzria.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtxbwpzimn.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gtuhwlokrc.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtfsbjnrsx.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfahxldrd.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gteftcbkpr.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtphuvixzz.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtldoagmrk.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gtcrbpkclm.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtkxxjbard.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gttegclctw.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtygfibafb.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtdaxwjbqj.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gttlhtjall.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtiyivgnkx.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtndmobbhn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtnxtvktic.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqbabgbhb.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gttzhehirm.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gttouxfvjs.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtvwuhqnrk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtikctfaqn.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtpennjcrg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtuyusacji.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtqhdfxkwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtozveevxv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtffxrmdxc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtqvcwbzif.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtimfympqf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gtcsxifgxy.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtlrxhhyfl.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtinxzctja.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtbjyckbcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtzpfcpnop.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gterwmyjsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtraetwhih.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtmpijhrpy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhutqmq.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtljeynlde.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtstyjxbzz.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtzbdzbhys.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtdoizxpni.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtvbkjgdox.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtxfmilxbt.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtgtetsmqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtsafwookq.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtsqsnpntx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gttagztqli.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtbtlichpp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtwmjjkbzt.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtcnpdwbmc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtpdjdkvii.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtxqmweggu.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gtlhymznxq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gttjifibyy.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gtjxcutixu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gttfldidlk.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdhneqqvz.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gtsvsduyqc.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtcjxqficf.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtjeuadkae.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gtjfzztsxr.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtpdazdddd.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtbksxsdyi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtkldnukcq.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtgknxeeop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtjfdtmxra.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtudemzocc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtdjypvscq.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtrqbyaagu.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtmrywmvcy.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtjoebnaew.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtaxkzeeum.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtcvtayvts.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtpodvsjzr.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtsvudloxo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gttyifqmqe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcgggqscr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtovivaehc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdwqfrnrm.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtmuaafevj.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtwvmmuxgp.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gttzifzeon.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsinoszuy.html


<!-- 参考信息 -->