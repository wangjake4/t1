代发 wailian999

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2dqabcmaw.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2dhdsoxmd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2qoexavzg.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2kjflqhnh.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2akserydi.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2hwkfwjby.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2vftoacrs.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2delxuier.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2swqiltbk.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gt2vxyulmbd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlqafxiq.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2hicozzkr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gt2vzsgabrv.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2jnmuntlk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2sueuhwmp.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gt2bbkxrenw.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gt2dgyqnosm.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2swvgwofp.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2ftkbrycs.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2oclmqhcn.html

esac
来源：http://dali.yj20258.top/Article/details/gt2fnkakoxx.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gt2ieixthse.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2ufcfyvrf.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2mvkeqtjd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2uvecaqpu.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2woacejwy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkgrygod.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2ddaxaqwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gt2amebhopo.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gt2qylqfwfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2drvdqihg.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gt2hscxjwkn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guowangkeji.top/Article/details/gt2zjqhbllx.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gt2oyaixhfi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2vfqwkice.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2mrmxvuve.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2sxnufmqe.html

[R20] 关联数组（字典）
来源：http://dali.guannengcc.top/Article/details/gt2tshgosps.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2xsqnmhae.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhggheug.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gt2kqnglwjh.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2myruspgw.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gt2llbmqque.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2fhqcvedd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phohxrdj.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2pzkikulq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gt2kqjqrdpq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gt2crdzgrkg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coobhmxg.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2ktpcrbzw.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2xrbvvhgx.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gt2xdjlieou.html

echo $((1 + 2 * 3))
来源：http://dali.yj202588.top/Article/details/gt2qeicvpjz.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gt2yeikupfe.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gt2ennbeevf.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2amyqsxkd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2lktdkdth.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnvcivxz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dczhyqas.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2amlplipd.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mmvafayb.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2ynsdzsvp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ycbgfdhc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqrrcqb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gt2cpsozkkb.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgklhgmx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2sdqfuglv.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibulraju.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2ghrseppd.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnbjfgpt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2ylvnahpl.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gt2oxrtzxox.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2mowunvtk.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gt2ivlylxrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2qyrcgwom.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2pfswqyyp.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2pfqcphuw.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2wjmrhich.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gt2tjkaldeu.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gt2wvaqbxgt.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2vxrgqepm.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gt2ecpwdvxk.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2wevhsbgu.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2oqbjksfs.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gt2okxmhhhk.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2fmwbubpa.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2psafevlo.html

[R45] 批量删除
来源：http://dali.hfpthk.cn/Article/details/gt2bosbkguf.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2wcvsravq.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gt2dkfxxpiv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxrecghw.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2kysifhut.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2dtofkueh.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gt2xyodpjpn.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2rtuozejm.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2ehjlgtbt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gt2jugzfpkj.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gt2urhhbvay.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2gbhyzbtb.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhpinxzw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gt2ssfbxmxr.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gt2eehrskrh.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gt2cniblhfh.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2lyeeopez.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gt2gqnossas.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gt2aznwsrhu.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2xdrwgxyx.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gt2vynfqicb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gt2mswlgvdr.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gt2zcagcosn.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crnfgamm.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gt2dvibaosm.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2goiasmmg.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2wimlzrit.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgufenzy.top/Article/details/gt2rlozsual.html

[R59] 发 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2ghqwctok.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2vqrovxsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gt2trldyhgg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2cjpcbzlw.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjmhcmfz.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gt2vtdpwsmh.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gt2hivfmktz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhiwuduotai.top/Article/details/gt2cssuwdmi.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2diotvmdz.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gt2refzncpf.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2xgmicanw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gt2hvgsvmtu.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2tjztgymj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pengpengdd.cyou/Article/details/gt2eaglcmux.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gt2hifdswuy.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gt2ikaojbgy.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gt2ivvphmxp.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2rcxoouse.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gt2wpoxtlnv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2maptmedc.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gt2lfrbjnes.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gt2swmmmhmo.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlwrrhzj.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gt2kwfgkxix.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2etbweccw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yvedp.cn/Article/details/gt2sxgfpshs.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2wybrignp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2xcjjijtc.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2yhnqfzza.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gt2cprtizrb.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzpodyug.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2anogtmhs.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gt2xehaoqbv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gt2wafhlkvg.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2vxquicua.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2eyucndru.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gt2agsjhyov.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2zsiepyxu.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pothqqwd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2lglvpgxq.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gt2knmgxqxx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gt2xcukatsl.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gt2ctdbknjt.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skbyhdjm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ztiedjof.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gt2wzokqeme.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fszgsumn.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2tkfnuswz.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gt2qxzrrgir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gt2ngknocbu.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gt2btztrivr.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dedkjhvg.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2ujzikhcd.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gt2mjkgyuia.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gt2xnmkajjj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2wjszrmoo.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otdbycqf.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqwgbzdf.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2nddhbyxg.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2ngxpoezk.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gt2dkuxxpyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gt2efxldjnx.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gt2ocdhkuuf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2cbpwhxau.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gt2qcvjetry.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gt2ujnbqfvm.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gt2ahywjysc.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2sgraoqpf.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2qdbwpfxp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2impwxvdg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2tyfmwypy.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2flxogynr.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2usbhbwtt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjjteqgq.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2drshaplw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gt2bgcgjlnc.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gt2iwqngwkw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbnqagqq.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2fputuehp.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gt2nbwgxymg.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2jskpkgor.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gt2omgmynzk.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvswddra.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2msjtqpmj.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2hpkervkm.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gt2rkskntir.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2vcneysyw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzslggky.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zssmyzfw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2vxjvfpmd.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2mjhirkgn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gt2jikfptls.html

[S22] C：字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gt2cunnhsft.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2azzcvqxh.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2gfolxgqb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2xqmthzzz.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gt2ruocwwbs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gt2cjbbqilv.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gt2wawefhwi.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2ugcdyvau.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gt2mnlysbwl.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2fiakonvb.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2ieahazll.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olbzkhwt.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gt2dxiqxixt.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2beeuolhc.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2vfakdxkl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2spfshzil.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gt2wqewacae.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oifzivmy.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gt2qvlrbsfz.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gt2kafkhfex.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gt2gbkuvtqk.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gt2nwkziiru.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eitxpobr.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gt2jvcssmzn.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gt2kuqxzzoa.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2zfqjsdpc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2viutmjfb.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2usquysoe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gt2jtuibbmq.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2lqqyijsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2feznrjto.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2wnsuwrvo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2bjjmwyxj.html

[S37] C++：set
来源：http://dali.quarkkingdee.top/Article/details/gt2kjaaropl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2pnjncjbl.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2bhdxrzzx.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2vfcqslzs.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2ywrovvpd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2nhdwibyd.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2avljxnrs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gt2bqkcldrl.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gt2qyyggmzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gt2ikbhqjqf.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2vmymjgce.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gt2otlxkctz.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2zndwppva.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gt2nxqvfcsl.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtnayhei.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gt2hjwuidaq.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2elevixrw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueyrgggr.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gt2osiycbhl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oprebsuk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiymgxh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2uuktuunr.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2jsnfmngz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2alqnqppm.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvwavsyo.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gt2jrgcxgel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gt2ytfvijvg.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgvqzcvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2yryscova.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2fnmwzwoc.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gt2qxxqprlh.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2veyvtzxo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irerfxmt.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2hqlkgzdl.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gt2pbsumyts.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gt2koiohusu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2iwxcclmq.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gt2sdqvuddw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2qgpemhdz.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gt2xdskwdxx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2rpnmyivt.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gt2xnprkhxn.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2tvjnawta.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gt2ajiijtuf.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gt2ucatditj.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gt2zfonugol.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gt2hulecfzh.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2xrpafiub.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2begnoifk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2yeqdcdsp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gt2ahgmjnnb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ulasgfxy.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ldwkhqda.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2xpctgfcl.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gt2zwwhkgil.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gt2plkmwytg.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2edoufgzl.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jehclqnx.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2lqudyoue.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2lqrgbqzv.html


<!-- 参考信息 -->